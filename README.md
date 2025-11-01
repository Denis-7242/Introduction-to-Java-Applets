# Introduction to Java Applets – Training Manual

A professional, interactive web-based presentation about Java Applets, their history, usage, and eventual deprecation.

![Presentation Preview](https://img.shields.io/badge/Slides-12-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Presentation Outline](#presentation-outline)
- [Technologies Used](#technologies-used)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 🎯 Overview

This is a modern, tech-themed presentation that provides a comprehensive introduction to Java Applets. The presentation covers their definition, history, advantages, limitations, and the reasons behind their deprecation. It's designed for educational purposes and training sessions.

## ✨ Features

- **12 Professional Slides**: Complete coverage of Java Applets topic
- **Modern Design**: Clean blue gradient theme with Poppins font
- **Interactive Navigation**: Click buttons or use keyboard arrows
- **Responsive Layout**: Adapts to different screen sizes
- **Smooth Animations**: Slide transitions and hover effects
- **Code Examples**: Syntax-highlighted code blocks
- **Visual Diagrams**: Interactive lifecycle diagram
- **No Dependencies**: Pure HTML, CSS, and JavaScript (except Google Fonts)

## 🎥 Demo

Open `index.html` in any modern web browser to view the presentation.

## 🚀 Installation

### Quick Start

1. **Clone or Download** this repository:
```bash
git clone https://github.com/yourusername/java-applets-presentation.git
```

2. **Navigate** to the project folder:
```bash
cd java-applets-presentation
```

3. **Open** `index.html` in your browser:
   - Double-click the file, or
   - Right-click → Open with → Your Browser, or
   - Use a local server (recommended for best experience)

### Using a Local Server (Recommended)

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server package)
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📖 Usage

### Navigation

- **Next Slide**: Click "Next →" button or press `Right Arrow` key
- **Previous Slide**: Click "← Previous" button or press `Left Arrow` key
- **First Slide**: Buttons are disabled on the first slide
- **Last Slide**: Buttons are disabled on the last slide

### Presentation Mode

Simply open the HTML file and present! The presentation is:
- Full screen optimized
- Keyboard navigation ready
- Professional and distraction-free

## 📊 Presentation Outline

1. **Title Slide** - Introduction and author information
2. **What is a Java Applet?** - Definition and brief history
3. **Why Use Applets?** - Advantages and common uses
4. **Limitations and Decline** - Plugin issues, security, deprecation
5. **Applet Structure Example** - Java code demonstration
6. **Applet Lifecycle** - Five key methods (init, start, paint, stop, destroy)
7. **Embedding Applets in HTML** - HTML `<applet>` tag example
8. **Types of Applets** - Local, remote, and signed applets
9. **Security & Sandbox** - Restricted environment explanation
10. **Why Applets Became Obsolete** - Modern alternatives
11. **Summary & Takeaways** - Key points and historical significance
12. **Thank You** - Closing slide

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling, animations, and gradients
- **JavaScript (Vanilla)** - Navigation logic and interactivity
- **Google Fonts** - Poppins font family

### No External Libraries Required!

This presentation uses pure web technologies without any frameworks or libraries (except Google Fonts CDN).

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` (Right Arrow) | Next slide |
| `←` (Left Arrow) | Previous slide |

## 🎨 Customization

### Changing Colors

Edit the CSS gradient values in the `<style>` section:

```css
/* Main gradient background */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Header/Footer gradient */
background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
```

### Changing Fonts

Replace the Google Fonts link in the `<head>`:

```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;600;700&display=swap" rel="stylesheet">
```

Then update the CSS:

```css
font-family: 'YourFont', sans-serif;
```

### Adding/Removing Slides

1. Copy an existing slide `<div class="slide">...</div>`
2. Paste and modify the content
3. Update the slide number display
4. Update `totalSlides` variable is calculated automatically

### Modifying Author Name

Search for "Denis Murithi" and replace with your name in:
- Title slide
- All slide footers
- Thank you slide

## 🌐 Browser Support

Tested and working on:

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)

**Minimum Requirements:**
- Modern browser with ES6 support
- JavaScript enabled
- Screen resolution: 1024x768 or higher (recommended)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions

- Add more slides with additional content
- Improve animations and transitions
- Add print/export to PDF functionality
- Create themes (dark mode, different color schemes)
- Add slide thumbnails/overview mode
- Implement touch gestures for mobile devices

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Denis Murithi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👤 Author

**Denis Murithi**

- Training Manual Series
- Presentation Created: 2025

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/java-applets-presentation/issues) page
2. Open a new issue if needed
3. Provide details about your browser and operating system

## 🙏 Acknowledgments

- Java history and documentation from Oracle
- Design inspiration from modern web presentations
- Google Fonts for the Poppins font family

---

**⭐ If you find this presentation useful, please give it a star!**

Made with ☕ and 💙 by Denis Murithi