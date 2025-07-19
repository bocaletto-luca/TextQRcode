# TextQRcode

TextQRcode is a lightweight, browser-based application that instantly converts any text or URL you enter into a high-resolution QR code. Designed with usability and performance in mind, it requires no server, frameworks, or installations—just paste your content and click. The app supports dynamic resizing, high error correction level, and seamless integration into websites or presentations. It’s ideal for sharing links, contact information, product details, or any block of text across devices. With a clean interface, SEO optimization, and a responsive design, TextQRcode ensures your audience can easily scan and access your content whether they’re on desktop, tablet, or mobile. Author Bocaletto Luca has crafted every aspect—from metadata and structured data for search engines to a minimal footprint—for a professional user experience.

[![Try Demo](https://img.shields.io/badge/Try%20Demo-Online-blue?style=for-the-badge)](https://bocaletto-luca.github.io/TextQRcode/index.html)

---

## Table of Contents

- [Features](#features)  
- [Demo](#demo)  
- [Getting Started](#getting-started)  
- [Usage](#usage)  
- [Customization](#customization)  
- [File Structure](#file-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Author](#author)  

---

## Features

- Pure client-side QR Code generation with no dependencies beyond a single HTML file  
- Real-time text or URL conversion into a 256×256 QR code with high error correction (H)  
- Clean, responsive design optimized for desktop, tablet, and mobile  
- SEO-friendly metadata, Open Graph tags, and JSON-LD structured data  
- Copy, clear, and regenerate controls for seamless workflow  
- No installation required—works offline once loaded in the browser  
- Accessible keyboard-focusable buttons and ARIA-compatible elements  

---

## Demo

Experience the live demo on GitHub Pages:  
https://bocaletto-luca.github.io/TextQRcode/index.html

---

## Getting Started

These instructions will help you run TextQRcode locally or on your own server.

### Prerequisites

Any modern web browser. No additional software needed.

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/bocaletto-luca/TextQRcode.git
   cd TextQRcode
   ```
2. **Serve the files**  
   Use a simple HTTP server to avoid CORS issues:
   ```bash
   # Python 3
   python3 -m http.server 8000
   # Node.js (http-server)
   npx http-server . -p 8000
   ```
3. **Open Your Browser**  
   Navigate to `http://localhost:8000/index.html`.

---

## Usage

1. **Enter Text or URL**  
   Click inside the editor textarea and type or paste any content.  
2. **Generate QR Code**  
   Press the **Generate QR** button to render a new code below.  
3. **Clear**  
   Use the **Clear** button to reset the editor and remove the current QR code.  
4. **Scan & Share**  
   Open the QR image on any device camera or scanning app to access your content instantly.

---

## Customization

- **QR Size & Styles**  
  Modify the `width` and `height` values in the `<script>` section to adjust QR dimensions.  
- **Error Correction**  
  Change the `correctLevel` in the QRCode configuration (`L`, `M`, `Q`, `H`) for different tolerances.  
- **Styling**  
  Tweak the embedded CSS in the `<style>` block or extract it to an external `style.css`.  
- **Metadata**  
  Update `<meta>` tags, Open Graph properties, and JSON-LD data in the `<head>` for your domain.  

---

## File Structure

```
TextQRcode/
├── index.html       # All-in-one application file (HTML, CSS, JS)
└── README.md        # This document
```

---

## Contributing

Contributions, issues, and feature requests are welcome:

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m "Add my feature"`)  
4. Push to your branch (`git push origin feature/my-feature`)  
5. Open a Pull Request  

Please ensure code consistency and test new features across major browsers.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Repository: [TextQRcode](https://github.com/bocaletto-luca/TextQRcode)
