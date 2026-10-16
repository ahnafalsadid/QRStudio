# QR Studio Generator

A modern, responsive QR-code generator built with **HTML, CSS, and JavaScript** in a single HTML file.

Create QR codes for websites, plain text, email addresses, phone numbers, and Wi-Fi networks, then download them as PNG or SVG files.

## Features

- **Single-file app** — the interface and application logic are contained in one HTML file.
- **Modern, responsive UI** — designed to work on desktop and mobile screens.
- **Multiple QR content types**
  - Website / URL
  - Plain text
  - Email
  - Phone number
  - Wi-Fi network details
- **Customization** — choose foreground and background colors, output size, and error-correction level.
- **Export options** — download generated QR codes as PNG or SVG.
- **No build step** — no Node.js, bundler, or package installation is required to open the page.

## Getting started

1. Download or clone this repository.
2. Open `qr_studio_generator.html` in a modern web browser.
3. Choose a content type and enter the information you want to encode.
4. Customize the appearance if desired.
5. Generate the QR code and download it as PNG or SVG.

### Run locally

No local web server is required for the standard version. You can open the HTML file directly in your browser.

## Internet requirement

The current version loads its QR-code generation library from a CDN. **An internet connection is required for the library to load**, and network filters, browser extensions, or blocked CDN domains may prevent generation from working.

If the library fails to load, check that your network can access the configured CDN URLs, or use a future bundled/offline version of the project.

## Project structure

```text
.
├── qr_studio_generator.html
├── README.md
└── LICENSE
```

## Technologies

- HTML5
- CSS3
- JavaScript
- QR-code library loaded from a CDN

## Browser support

Use a recent version of Chrome, Firefox, Edge, or Safari. Export behavior may vary slightly by browser.

## Contributing

Contributions, bug reports, and suggestions are welcome.

1. Fork the repository.
2. Create a branch for your change.
3. Make and test your changes.
4. Open a pull request describing the improvement.

For bug reports, include your browser, operating system, steps to reproduce the issue, and any relevant console error messages. Do not include private Wi-Fi passwords or other sensitive information in public issue reports.

## License

This project is released under the MIT License. See [`LICENSE`](LICENSE) for details.

---

Made with ❤️ for simple, customizable QR-code creation.
