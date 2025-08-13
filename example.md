# Markdown Showcase Document

This document demonstrates all the markdown features supported by the Markdown File Viewer.

## Table of Contents

- [Headers](#headers)
- [Text Formatting](#text-formatting)
- [Lists](#lists)
- [Links and Images](#links-and-images)
- [Code](#code)
- [Tables](#tables)
- [Blockquotes](#blockquotes)
- [Horizontal Rules](#horizontal-rules)
- [GitHub Flavored Markdown](#github-flavored-markdown)

---

## Headers

# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

## Text Formatting

**Bold text** and __also bold__

*Italic text* and _also italic_

***Bold and italic*** and ___also bold and italic___

~~Strikethrough text~~

Regular text with `inline code` formatting.

## Lists

### Unordered Lists

- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
    - Deep nested item
- Item 3

### Ordered Lists

1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item

### Task Lists

- [x] Completed task
- [x] Another completed task
- [ ] Incomplete task
- [ ] Another incomplete task

## Links and Images

[Link to Google](https://google.com)

[Link with title](https://github.com "GitHub Homepage")

Auto-converted link: https://www.example.com

Reference-style link: [GitHub][1]

[1]: https://github.com

### Images

![Alt text](https://via.placeholder.com/300x200.png?text=Sample+Image)

![Alt text with title](https://via.placeholder.com/200x150.png?text=Another+Image "Image Title")

## Code

### Inline Code

Use `npm install` to install packages.

The `console.log()` function prints to the console.

### Code Blocks

Plain code block:

```
function hello() {
    console.log("Hello, world!");
}
```

JavaScript with syntax highlighting:

```javascript
const greeting = "Hello, world!";

function greet(name) {
    return `Hello, ${name}!`;
}

// Arrow function
const add = (a, b) => a + b;

console.log(greet("Developer"));
```

Python example:

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

# List comprehension
squares = [x**2 for x in range(10)]
print(squares)
```

HTML example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>My Heading</h1>
    <p>My paragraph.</p>
</body>
</html>
```

CSS example:

```css
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 4px;
    cursor: pointer;
}

.button:hover {
    background-color: #0056b3;
}
```

JSON example:

```json
{
    "name": "John Doe",
    "age": 30,
    "city": "New York",
    "hobbies": ["reading", "swimming", "coding"],
    "address": {
        "street": "123 Main St",
        "zipCode": "10001"
    }
}
```

## Tables

| Name | Age | City | Occupation |
|------|-----|------|------------|
| John | 25 | NYC | Developer |
| Jane | 30 | LA | Designer |
| Bob | 35 | Chicago | Manager |

### Table with Alignment

| Left Aligned | Center Aligned | Right Aligned |
|:-------------|:--------------:|--------------:|
| Left | Center | Right |
| Text | Text | Text |
| More content | More content | More content |

## Blockquotes

> This is a simple blockquote.

> This is a blockquote with multiple paragraphs.
>
> Here's the second paragraph in the blockquote.

> ### Blockquote with other elements
>
> - Lists work in blockquotes
> - **Bold text** also works
> - `Inline code` works too

Nested blockquotes:

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

## Horizontal Rules

---

***

___

## GitHub Flavored Markdown

### Fenced Code Blocks

```bash
# Install dependencies
npm install

# Run the development server
npm run dev

# Build for production
npm run build
```

### Tables (Extended)

| Feature | Supported | Notes |
|---------|-----------|-------|
| Headers | ✅ | All levels (H1-H6) |
| **Bold** | ✅ | Multiple syntaxes |
| *Italic* | ✅ | Multiple syntaxes |
| `Code` | ✅ | Inline and blocks |
| Links | ✅ | Multiple formats |
| Images | ✅ | With alt text |
| Tables | ✅ | With alignment |
| Lists | ✅ | Ordered, unordered, nested |
| Blockquotes | ✅ | With nesting |
| ~~Strikethrough~~ | ✅ | GitHub extension |
| Task lists | ✅ | Interactive checkboxes |

### Syntax Highlighting Examples

SQL:
```sql
SELECT users.name, COUNT(orders.id) as order_count
FROM users
LEFT JOIN orders ON users.id = orders.user_id
WHERE users.active = true
GROUP BY users.id
ORDER BY order_count DESC;
```

Shell/Bash:
```bash
#!/bin/bash
for file in *.md; do
    echo "Processing $file"
    pandoc "$file" -o "${file%.md}.html"
done
```

### Line Breaks and Paragraphs

This is a paragraph with a soft line break.
This line is part of the same paragraph.

This is a new paragraph.

This paragraph has two spaces at the end.  
This creates a line break within the same paragraph.

---

## Special Characters and Escaping

You can escape special characters with backslashes:

\*This is not italic\*

\`This is not code\`

\# This is not a header

\[This is not a link\]

## Conclusion

This example file demonstrates the comprehensive markdown support in the Markdown File Viewer. All these elements should render beautifully with GitHub-style formatting, syntax highlighting, and proper spacing.

Feel free to edit this file and reload it in the viewer to test different markdown features!