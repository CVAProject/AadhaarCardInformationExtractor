# Aadhaar Card Information Extractor
This project is an implementation of OCR (Optical Character Recognition) to extract relevant information from an Aadhaar card.

## Setup
1. Install the required packages by running pip install -r requirements.txt.
2. Download and install Tesseract OCR from here.
3. Set the Tesseract OCR engine path in the code.
4. Set the input image path in the code. For example, `frame = cv2.imread('ss_aadhaar.jpg')`

## Usage
1. Run the code `python aadhaar_ocr.py`.
2. The input image, warped image, and processed image will be displayed.
3. The extracted text (Aadhaar number, name, DOB, and gender) will be printed in the console.
