# Thomas Ogbemudia's Resume Website

A simple two-page website that displays a resume PDF and provides a QR code for easy sharing.

## Pages

1. **Home Page** (`index.html`)
   - Displays the resume PDF in a full-width viewer
   - Clean, responsive design
   - Navigation to QR code page

2. **QR Code Page** (`qr.html`)
   - Generates a QR code for tom.glamboyosa.xyz
   - Responsive design
   - Smart navigation that only shows "Back to Resume" when accessed from the main site

## Project Structure

```
.
├── index.html          # Main page with PDF viewer
├── qr.html            # QR code generator page
├── public/            # Static assets
│   └── Thomas Ogbemudia C.V 2025 (Resume).pdf
└── README.md          # This file
```

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) for QR code generation

## Deployment

This site is designed to be deployed on Vercel. The PDF viewer will work as long as the PDF file remains in the `public` directory.

## Features

- Responsive design that works on all devices
- PDF viewer with full-width display
- Smart QR code generation
- Conditional navigation based on referrer
- Clean, modern UI with subtle animations 