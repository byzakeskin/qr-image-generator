# QR Image Generator

This is a simple **Node.js CLI application** that generates a QR code image from a user-provided URL.

## Features
- Takes URL input directly from the terminal.
- Generates a **QR code image (`qr_image.png`)**.
- Saves the provided URL to a `URL.txt` file.
- Uses:
  - [`inquirer`](https://www.npmjs.com/package/inquirer) → for interactive prompts  
  - [`qr-image`](https://www.npmjs.com/package/qr-image) → for QR code generation  
  - [`fs`](https://nodejs.org/api/fs.html) → for file system operations  

## Installation & Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/byzakeskin/qr-image-generator.git
   cd qr-image-generator

2. Install dependencies:

npm install

3. Run the app:

node index.j

4. Type your URL when prompted. The app will:

Save the URL to URL.txt

Generate a QR image as qr_image.png

📂 Example Output

Type your URL: https://example.com
The URL has been saved!

Generated files:

URL.txt
qr_image.png
