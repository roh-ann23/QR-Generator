# QR Code Generator

This is a simple web-based application that allows users to generate QR codes by entering text or URLs. The project is created using HTML, CSS, and JavaScript and utilizes a QR code generator API for creating QR codes dynamically.

## Features

- **Input Field:** Users can enter text or URLs for which they want to generate QR codes.
- **QR Code Display:** Upon clicking the "Generate QR Code" button, the QR code corresponding to the entered text or URL is displayed.
- **Error Handling:** If the input field is empty when the button is clicked, an error message is displayed briefly to prompt the user to enter text or a URL.
- **Responsive Design:** The application is designed to be responsive, ensuring usability across various devices and screen sizes.

## Project Structure

- **index.html:** The main HTML file containing the structure of the QR code generator app.
- **style.css:** CSS file for styling the app.
- **script.js:** JavaScript file with the logic for generating QR codes.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/roh-ann23/qr-code-generator.git
    ```

2. Open `index.html` in a web browser.

3. Enter the text or URL for which you want to generate a QR code into the input field.

4. Click the "Generate QR Code" button to generate the QR code.

## Code Explanation

- **HTML (index.html):** Contains the structure of the QR code generator app, including the input field, QR code display area, and the button to generate QR codes.
- **CSS (style.css):** Provides styles for the app elements, including layout, positioning, and aesthetics.
- **JavaScript (script.js):** Implements the functionality for generating QR codes based on user input and updating the QR code display accordingly.

## QR Code Generator API

This application utilizes the QR code generator API to dynamically create QR codes based on user input. The API endpoint used is `https://api.qrserver.com/v1/create-qr-code/`, which generates QR codes in PNG format.
