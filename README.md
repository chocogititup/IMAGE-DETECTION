# Image Detection with OCR

## Overview
This project focuses on detecting objects in images and extracting text using Optical Character Recognition (OCR). It combines image processing techniques with OCR to recognize and extract meaningful text from various sources such as scanned documents, images, and screenshots.

## Features
- Object detection in images
- Text extraction using OCR
- Preprocessing for better OCR accuracy
- Support for multiple image formats (JPG, PNG, etc.)
- Integration with Tesseract OCR

## Technologies Used
- Python
- OpenCV
- Tesseract OCR
- NumPy
- Pillow (PIL)
- Matplotlib (for visualization)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/image-detection-ocr.git
   cd image-detection-ocr
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install Tesseract OCR:
   - Windows: Download from [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
   - Linux (Ubuntu/Debian):
     ```bash
     sudo apt install tesseract-ocr
     ```
   - macOS (using Homebrew):
     ```bash
     brew install tesseract
     ```

## Usage
Run the script to perform image detection and OCR:
```bash
python main.py --image path/to/image.jpg
```

### Example
```bash
python main.py --image sample.jpg
```
Output:
```
Detected Text: "Hello, World!"
```

## Configuration
Modify `config.py` to adjust OCR parameters and preprocessing settings.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


