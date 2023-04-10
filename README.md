# ChatGPT to PDF Converter Chrome Extension

A Chrome extension to convert ChatGPT responses on a web page into a PDF file.

## Features

- Extract ChatGPT responses from web pages
- Generate a PDF file with the extracted responses
- Customize PDF output (fonts, colors, layout)
- Capture and include images in the PDF (optional)

## Installation

1. Clone or download this repository to your local machine.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" using the toggle in the top right corner.
4. Click the "Load unpacked" button and select the extension's folder.
5. The ChatGPT to PDF Converter extension should now be installed and visible in your browser toolbar.

## Usage

1. Navigate to a web page containing ChatGPT responses.
2. Click the ChatGPT to PDF Converter icon in the browser toolbar.
3. In the extension popup, click the "Convert to PDF" button.
4. The extension will extract ChatGPT responses and generate a PDF file.
5. The PDF file will be downloaded to your default downloads folder.

## Customization

- To customize the PDF output, modify the `popup.js` file, changing fonts, colors, and layout using jsPDF's API.
- To include images in the PDF, use the `html2canvas` library to capture images and include them in the PDF. See the example code in the previous response.
- To implement a user interface for custom settings, modify the `popup.html` file, adding form elements for user input and using these values in the `popup.js` file.

## Troubleshooting

- If the extension does not work as expected, open the browser console (Ctrl + Shift + J or Cmd + Opt + J on Mac) and check for any error messages or warnings.
- Ensure that the extension is compatible with the website's DOM structure. You may need to modify the code to accurately extract ChatGPT responses from different websites.

## Contributing

1. Fork this repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Create a pull request detailing the changes made and their purpose.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
