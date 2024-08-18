# QR Code Generator

This simple web application allows users to generate QR codes from text or URLs. It provides a user-friendly interface to input data and instantly see the corresponding QR code image.

## Features

- **Easy to Use:** Simply enter the desired text or URL, and click "Generate QR Code" to view the result.
- **Dynamic QR Code Generation:** QR codes are generated dynamically using an external API.
- **Error Handling:** Input validation with visual feedback for empty submissions.

## Usage

- **Open the application:** Open `index.html` in your preferred web browser.
- **Enter Text or URL:** In the input field labeled 'Text or URL', enter the data you want to convert into a QR code.
- **Generate QR Code:** Click the 'Generate QR Code' button. The QR code will appear below the input field.
- **Error Handling:** If the input field is left empty and 'Generate QR Code' is clicked, the input field will shake and highlight, prompting you to enter some text.

## Technologies Used

- **HTML5**
- **CSS3:** Includes animations and responsive design.
- **JavaScript:** For handling QR code generation and user interactions.

## Custom Styles and Animations

- **Container Glow:** The main interface container has a glowing effect that cycles through various colors.
- **Input Validation Animation:** An error shake animation triggers if the generate button is clicked with an empty input field.

## External API

- QR Code images are generated using [this API](https://api.qrserver.com/v1/create-qr-code/), which requires a parameter for size and the data to encode.
