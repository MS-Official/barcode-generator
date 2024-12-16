## Barcode Generator

A simple barcode generator application built using Python and PyQt5. This tool allows users to input data, generate barcode previews, and save the barcode as an image file. It supports generating Code128 barcodes and provides a user-friendly interface for easy barcode creation.

## Features

- Input data for barcode generation
- Live preview of the barcode as you type
- Save the generated barcode to a specified directory
- Supports Code128 barcode format
- Simple and intuitive user interface built with PyQt5

## Installation

To get started, you need to have Python and PyQt5 installed. Follow these steps:

1. Clone this repository:

   ```bash
   git clone https://github.com/MS-Official/barcode-generator.git
   cd barcode-generator
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
    OR
   ```bash
   pip3 install -r requirements.txt
   ```

3. Install the `python-barcode` library for barcode generation:

   ```bash
   pip install python-barcode
   ```
   OR
   ```bash
   pip3 install python-barcode
   ```

# Usage

1. Run the application:

   ```bash
   python barcode_generator.py
   ```
   OR
   ```bash
   python3 barcode_generator.py
   ```

3. Enter the data you want to encode into a barcode in the "Enter Data" field.
4. The barcode preview will update as you type.
5. Choose a directory where you want to save the barcode by clicking the "Browse" button.
6. Click the "Generate Barcode" button to create and save the barcode as a PNG image in the selected directory.

## Example

- Enter "123456789" as data.
- Click "Generate Barcode" to save the barcode in the selected directory.

## Requirements

- Python 3.x
- PyQt5
- python-barcode

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork this project, open issues, and submit pull requests. Contributions are welcome!
