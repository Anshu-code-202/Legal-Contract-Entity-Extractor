# OCR-Based Text Processing and Named Entity Recognition (NER) Pipeline

## Project Overview
This project implements an end-to-end pipeline that extracts text from PDF documents using Optical Character Recognition (OCR) and processes the extracted text using Natural Language Processing (NLP) techniques. The system also sets up a Named Entity Recognition (NER) model to identify meaningful entities such as names, locations, and organizations from text.

The project is designed to automate document processing and convert unstructured document data into structured information.

---

## Objectives

### Week-1 Objectives
- Build an OCR pipeline to extract text from PDF files.
- Convert PDF pages into images.
- Extract text using OCR.
- Clean extracted text by removing noise and formatting errors.
- Save cleaned text into a structured file.

### Week-2 Objectives
- Analyze extracted text using statistical methods.
- Compare raw and cleaned text lengths.
- Perform word frequency analysis.
- Remove stopwords and visualize frequent words.
- Initialize and configure the Named Entity Recognition (NER) model.
- Define entity labels and save the model structure.

---

## Features
- PDF to image conversion
- OCR-based text extraction
- Text cleaning and preprocessing
- Word frequency analysis
- Text visualization using bar charts
- Named Entity Recognition (NER) pipeline setup
- Model saving for future use

---

## Project Workflow

PDF Document  
→ Convert PDF to Images  
→ Extract Text using OCR  
→ Clean Extracted Text  
→ Perform Text Analysis  
→ Initialize NER Model  
→ Save Model

---

## Technologies Used
- Python  
- Tesseract OCR  
- pdf2image  
- OpenCV  
- Pillow  
- spaCy  
- NLTK  
- Matplotlib  
- NumPy  



---

## Usage
- Provide input PDF file.
- Run OCR pipeline to extract text.
- Clean and process extracted text.
- Perform text analysis.
- Initialize and save the NER model.

----

## Sample Output
- Extracted text file from PDF.
- Cleaned text file (cleaned_text.txt).
- Bar chart showing word frequency.
- Saved NER model directory.

----

## Future Enhancements
- Complete NER model training.
- Improve entity detection accuracy.
- Add support for multiple document types.
- Build a user interface for document upload.
-Integrate real-time entity extraction.

---

## Author

Anshu Arora

B.Tech Computer Science Engineering

OCR and NLP Project Developer

---
---

## Installation

Install required dependencies:

```bash
pip install pytesseract pdf2image opencv-python pillow spacy nltk matplotlib numpy

---
Install Tesseract OCR and Poppler utilities based on your operating system.

