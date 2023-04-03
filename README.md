# Aadhaar Card Information Extractor
This project is an implementation of OCR (Optical Character Recognition) to extract relevant information from an Aadhaar card.

## Setup
1. Install the required packages by running pip install -r requirements.txt.
2. Download and install Tesseract OCR from here.
3. Set the Tesseract OCR engine path in the code.

## Usage
1. Run the code `python aadhaar_info_extractor.py image_name.jpg`, replace `image_name.jpg` with the filepath to your image.
2. The input image, warped image, and processed image will be displayed.
3. The extracted text (Aadhaar number, name, DOB, and gender) will be printed in the console.
