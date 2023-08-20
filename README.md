# Newspaper-Image-Processing-and-Face-Recognition

This project demonstrates image processing, text extraction, and face recognition using Python. It involves processing a collection of newspaper images stored in a ZIP file, searching for specific keywords in the text, detecting faces, and creating contact sheets to display the results.

## Project Overview

The main goal of this project is to create a Python script that can perform the following tasks:

1. Open a ZIP file containing newspaper images.
2. Iterate through the images and search for specific keywords in the text using Optical Character Recognition (OCR) with Tesseract.
3. Detect faces in images that contain the specified keywords using OpenCV's Haar Cascade Classifier.
4. Create contact sheets to display recognized faces and relevant information.

## Prerequisites

- Python 3.x
- Install required Python packages using the following command:

  ```bash
  pip install Pillow opencv-python pytesseract
  ```

## Acknowledgments

- Face detection is based on OpenCV's Haar Cascade Classifier.
- Text extraction is performed using Tesseract OCR.
- Image processing and display utilize the Pillow and matplotlib libraries.

## Credits

This project is based on Python Project: pillow, tesseract, and opencv course by University of Michigan on Coursera

