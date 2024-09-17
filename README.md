# OCR Form Field Extraction Project

## Overview

This project implements three different approaches for Optical Character Recognition (OCR) and field extraction from form images:
1. A custom OCR solution using Tesseract and natural language processing techniques.
2. A deep learning-based approach using LayoutLMv3, a state-of-the-art model for document understanding.
3. An advanced OCR solution using DocTR (Document Text Recognition) with custom field extraction logic.

All three solutions aim to identify and extract relevant information from uploaded form images.

## Features

- Image upload functionality
- Three processing methods:
  1. Custom OCR using Tesseract
  2. Deep learning-based using LayoutLMv3
  3. Advanced OCR using DocTR with custom field extraction
- Field extraction for predefined form fields
- Visualization of extracted bounding boxes
- JSON output of extracted field-value pairs
- Confidence scores for extracted fields (in DocTR approach)

## Installation

To run this project, you need to have Python installed along with the following libraries:

```
pip install ipywidgets Pillow pytesseract opencv-python numpy matplotlib torch transformers datasets seqeval doctr[torch]
```
![Screenshot 1](path/to/screenshot1.png)
