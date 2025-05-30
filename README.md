# SASS Website Template

A simple, responsive website template built with HTML and SASS/SCSS.

## 📋 Overview

This project demonstrates how to structure and organize a website using SASS (Syntactically Awesome Style Sheets) to create maintainable and modular CSS. It follows the 7-1 pattern for SASS architecture.

## 🚀 Features

- Clean, responsive design
- Modular SCSS file structure
- Mobile-first approach
- Easily customizable with variables
- No images used - perfect for learning fundamentals

## 🛠️ Tech Stack

- HTML5
- SASS/SCSS (with 7-1 architecture)
- Node.js (for SASS compilation)


## ⚙️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yashdubeyy/SassWebsite.git
   cd SassWebsite
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## 🖥️ Usage

### Development Mode

To work on the project with automatic SASS compilation:

```bash
npm run sass:watch
```

This will start a watch process that automatically compiles SCSS to CSS whenever changes are made.

### Build for Production

To generate a minified CSS file for production:

```bash
npm run sass:compressed
```

### One-time Compilation

To compile SCSS to CSS once:

```bash
npm run sass
```

## 📝 Customizing

1. Colors, fonts, and other global variables can be modified in `scss/abstracts/_variables.scss`
2. Component styles are in their respective files under `scss/components/`
3. Page-specific styles should go in `scss/pages/`

## 🛠️ Working with VS Code

For the best experience with VS Code:

1. Install these recommended extensions:
   - Live Server
   - SASS
   - Prettier - Code formatter

2. Use Live Server to preview your changes:
   - Right-click on `index.html`
   - Select "Open with Live Server"

3. Keep the SASS watcher running:
   - Open a terminal in VS Code (Ctrl+`)
   - Run `npm run sass:watch`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yashdubeyy/SassWebsite/issues).

## 👨‍💻 Author

- GitHub: [@yashdubeyy](https://github.com/yashdubeyy)
