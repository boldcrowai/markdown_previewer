# A Simple Markdown Viewer That Just Works

I built a little markdown file viewer the other day, and honestly, it's nothing revolutionary – but it's pretty handy for quickly previewing `.md` files without the friction of opening an IDE or switching to preview mode.

## The Problem (Sort Of)

Don't get me wrong, modern IDEs like Cursor have great markdown preview functionality. But sometimes you just want to open a markdown file and read it without dealing with all the IDE overhead. Maybe you're browsing through documentation, reviewing a README, or just want to see how your markdown looks rendered without opening your full development environment.

## What It Does

The tool is dead simple:
- Drag and drop any `.md`, `.markdown`, or `.txt` file
- Get a clean, GitHub-style rendered preview
- Keep track of recently opened files in a sidebar
- Syntax highlighting for code blocks
- Responsive design that works on any screen size

It uses the `marked` library for parsing and `Prism.js` for syntax highlighting, so the output looks pretty much like what you'd see on GitHub.

## Why I Like It

The main thing is navigation. When you're working with multiple markdown files – maybe comparing documentation across different projects or reviewing several README files – having that recent files sidebar makes jumping between them really smooth. 

IDEs are great when you're coding, but sometimes you just want to read. This tool strips away all the extra stuff and focuses on one thing: showing you markdown files in a clean, readable format.

## Try It Out

The whole thing is just a single HTML file with embedded CSS and JavaScript. No build process, no dependencies to install, no setup. Just open it in your browser and start dropping files.

You can grab it from my GitHub repo and use it however you want. It's one of those "small tools that solve small problems" situations – nothing fancy, but useful when you need it.

[**→ Get the Markdown Viewer on GitHub**](https://github.com/your-username/md-file-viewer)

---

*Sometimes the best tools are the simple ones that just do what they say they'll do.*