
# QR Code Generator

This is a simple **QR Code Generator** built using **HTML**, **Tailwind CSS**, and **JavaScript**. The generator allows users to input text or a URL and instantly generate a downloadable QR code.

## Features

- **Generate QR Codes**: Enter any text or URL, and generate a QR code on the fly.
- **Download Option**: After generating the QR code, users can download it as a PNG file.
- **Responsive Design**: The UI is fully responsive, optimized for both mobile and desktop devices.
- **Clean and Simple UI**: Designed using the **Tailwind CSS** framework to provide a minimalistic and sleek look.

## Technologies Used

- **HTML5**: For creating the structure of the webpage.
- **Tailwind CSS**: A utility-first CSS framework used for styling. It helps in creating a responsive, mobile-first design with minimal custom styles.
- **JavaScript**: Used to manage the logic of QR code generation, handling user input and displaying the QR code.
- **QR Code API**: The API `https://api.qrserver.com/v1/create-qr-code/` is used to generate the QR code image. The data entered by the user is passed to the API to create a QR code.

## Project Structure

The project consists of a single HTML file with embedded CSS and JavaScript. Below is an overview of the structure:

- **`index.html`**: The main HTML file containing:
  - **Tailwind CSS**: Used for styling the webpage elements.
  - **JavaScript**: To manage the QR code generation process and interact with the QR code API.

### File Breakdown:

- **HTML**:
  - The page has a simple form structure with an input field for the text or URL, a button to generate the QR code, and a section to display the generated QR code and download option.
  
- **Tailwind CSS**:
  - The layout uses a centered design with a dark theme for a modern and clean look.
  - Utility classes from Tailwind CSS are used for styling, making it simple to customize the look and feel.

- **JavaScript**:
  - Handles the logic for QR code generation, validation of user input, and interaction with the external API for generating the QR code image.

## How to Use

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/amuqtadir99/qr-code-generator.git
```

### 2. Open the `index.html` File

Open the `index.html` file in any modern web browser.

### 3. Enter Text or URL

Type any text or a valid URL into the input field.

### 4. Generate the QR Code

Click on the "Generate QR Code" button to generate the QR code.

### 5. Download the QR Code

Once the QR code is generated, you can click the "Download Now" button to download the QR code image.

## Live Demo

You can view the live demo of the QR Code Generator here:  
[QR Code Generator Demo](#)

## Author

Created by [Abdul Muqtadir](https://github.com/amuqtadir99) @witwebsolutions  
[Visit my website](https://www.witweb.com.au)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


