# Markdown Live Previewer

A powerful, feature-rich Markdown editor with real-time preview, syntax highlighting, and HTML export capabilities. Built with pure HTML, CSS, and JavaScript - no dependencies required!

![Markdown Live Previewer](https://img.shields.io/badge/markdown-editor-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🚀 Features

- ✨ **Real-time Preview** - See your markdown rendered instantly as you type
- 🎨 **Syntax Highlighting** - Beautiful code blocks with language-specific syntax highlighting powered by Highlight.js
- 📥 **Export to HTML** - Download your markdown as a standalone HTML file
- 📱 **Responsive Design** - Fully responsive layout that works on all devices
- 💾 **Auto-save** - Your content is automatically saved to browser's local storage
- ⌨️ **Keyboard Shortcuts** - Efficient workflow with keyboard shortcuts
- 🌙 **Dark Theme** - Easy on the eyes with a modern dark theme
- 📝 **Full Markdown Support** - Supports all standard markdown syntax including:
  - Headers (H1-H6)
  - Text formatting (bold, italic, strikethrough)
  - Lists (ordered and unordered)
  - Code blocks with syntax highlighting
  - Blockquotes
  - Links and images
  - Tables
  - Horizontal rules

## 🎯 Demo

Simply open `index.html` in your web browser to start using the editor. No build process or installation required!

## 💻 Usage

1. Open `index.html` in any modern web browser
2. Start typing markdown in the left panel
3. See the preview update in real-time on the right panel
4. Use the "Export HTML" button to download your content as an HTML file
5. Use the "Clear" button to start fresh

### Keyboard Shortcuts

- `Tab` - Insert 4 spaces (indentation)
- `Ctrl/Cmd + S` - Export to HTML

## 🛠️ Technologies Used

- **HTML5** - Structure and layout
- **CSS3** - Responsive styling with custom dark theme
- **JavaScript (ES6+)** - Interactive functionality and custom markdown parser

## 📦 Dependencies

**None!** This is a completely self-contained application with:
- Custom markdown parser (no external libraries needed)
- Custom syntax highlighting for code blocks
- Pure CSS responsive design (no framework required)

## 🌐 Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Opera

## 📝 Markdown Syntax Examples

The editor supports all standard markdown syntax. Here are some examples:

### Headers
```markdown
# H1 Header
## H2 Header
### H3 Header
```

### Text Formatting
```markdown
**bold text**
*italic text*
***bold and italic***
~~strikethrough~~
```

### Lists
```markdown
- Unordered list item
- Another item

1. Ordered list item
2. Another item
```

### Code
```markdown
Inline `code`

```javascript
// Code block with syntax highlighting
function hello() {
  console.log("Hello, World!");
}
```
```

### Links and Images
```markdown
[Link text](https://example.com)
![Alt text](image-url.jpg)
```

### Tables
```markdown
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
```

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

BaseMax

## 🎨 Design Philosophy

This project demonstrates that powerful web applications can be built without relying on external libraries or frameworks. The entire application is self-contained in a single HTML file with custom implementations for:
- Markdown parsing
- Syntax highlighting
- Responsive design
