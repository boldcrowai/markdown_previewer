# Markdown File Viewer

A simple, lightweight web-based markdown previewer that renders `.md`, `.markdown`, and `.txt` files with GitHub-style formatting.

## Features

- **Drag & Drop**: Simply drag markdown files onto the viewer
- **File Browser**: Use the file input to select files from your system
- **Recent Files Sidebar**: Quick access to recently opened files
- **GitHub-Style Rendering**: Clean, familiar markdown styling
- **Syntax Highlighting**: Code blocks with language-specific highlighting
- **Responsive Design**: Works on desktop and mobile devices
- **No Installation Required**: Single HTML file, runs in any modern browser

## Usage

### Quick Start
1. Download `index.html`
2. Open it in your web browser
3. Drag a markdown file onto the drop zone, or use the file input to select a file
4. View your rendered markdown instantly

### File Support
- `.md` files
- `.markdown` files  
- `.txt` files

### Recent Files
- Access recently opened files via the sidebar (click the 📁 icon)
- Files are automatically added when opened
- Remove individual files or clear all recent files
- Recent files persist during your browser session

### URL Loading
You can also load markdown files directly from URLs by adding a `file` parameter:
```
index.html?file=https://raw.githubusercontent.com/user/repo/main/README.md
```

## Technical Details

Built with:
- [Marked.js](https://marked.js.org/) for markdown parsing
- [Prism.js](https://prismjs.com/) for syntax highlighting
- Vanilla JavaScript (no frameworks)
- GitHub-inspired CSS styling

## Browser Compatibility

Works in all modern browsers that support:
- File API
- Drag and Drop API
- ES6 features

## Local Development

No build process required! Simply:
1. Clone or download the repository
2. Open `index.html` in your browser
3. Start using it immediately

## Use Cases

- Previewing README files before committing
- Reading documentation without opening an IDE
- Quickly viewing markdown files from file explorer
- Sharing rendered markdown with others
- Offline markdown viewing

## License

Feel free to use, modify, and distribute as needed.

---

**Note**: This tool runs entirely in your browser - no data is sent to any servers. All file processing happens locally on your machine.