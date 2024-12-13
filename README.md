This repository contains a robust image-to-text conversion system that leverages PaddleOCR for Optical Character Recognition (OCR). The system processes images, extracts text with high accuracy, and optimizes preprocessing techniques to enhance OCR performance. This solution is ideal for tasks requiring text extraction from images, such as document scanning, text analysis, or automated data entry.

Features
OCR with PaddleOCR: Utilizes the powerful PaddleOCR library to extract text from images in various formats.
Image Format Conversion: Converts images (e.g., PNG) to TIFF format for improved preprocessing.
Preprocessing Pipeline:
Resizes images using cubic interpolation to enhance text clarity.
Applies Gaussian Blur to reduce noise and improve OCR accuracy.
Efficient Text Extraction:
Processes the image and extracts text with classification for enhanced accuracy.
Converts recognized text into a single-line string for easy usage in downstream applications.
Workflow
Install Dependencies:
Installs PaddleOCR and required libraries (opencv-python, pillow, etc.).
Image Conversion:
Converts input images to TIFF format for better compatibility with preprocessing steps.
Image Enhancement:
Resizes the image using cubic interpolation.
Applies Gaussian blur for noise reduction.
OCR Execution:
Processes the enhanced image with PaddleOCR to extract text elements.
Text Formatting:
Combines the extracted text into a structured, single-line output.
Requirements
Python 3.7+
Libraries: paddlepaddle-gpu, paddleocr, opencv-python, pillow
