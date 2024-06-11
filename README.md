
# QR Image Generator

[Live Deployment](https://studiobloom.github.io/qr_image-main/)

This repository contains a JavaScript implementation for generating QR codes. It leverages the `qrcode` library to create QR codes from input text, displaying them as images on a webpage. Additionally, it allows users to combine an uploaded image with the generated QR code for custom image QR codes.

## Features

- Generate QR codes from any text input using uploaded image as background

## Getting Started

### Prerequisites

To use this project, you need the following:

- A modern web browser
- Basic knowledge of HTML and JavaScript

### Installation

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/studiobloom/qr_image-main.git
   ```

2. Navigate to the project directory:

   ```sh
   cd qr_image-main
   ```

3. Open `index.html` in your web browser to see the QR code generator in action.

### Usage

1. Open the `index.html` file in a web browser.
2. Enter the text you want to encode into a QR code in the input field.
3. Upload an image you want to combine with the QR code.
4. Click the "Generate QR Code" button.
5. The custom QR code will be displayed as an image below the input field.

## Files

- `index.html`: The main HTML file that contains the structure of the webpage.
- `qrcode.js`: JavaScript file that handles the QR code generation.
- `style.css`: CSS file for basic styling of the webpage.

## Dependencies

This project uses the following libraries:

- `qrcode`: A library to generate QR codes in JavaScript. You can find it [here](https://github.com/soldair/node-qrcode).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Credits
QR code generation library: Kazuhiko Arase
Copyright (c) 2009 Kazuhiko Arase
