# Table-detection-and-structure-recognition-using-deep-learning
"Document Structure Analysis" utilizes YOLOv8X and KeremErbas's YOLOv8M for table detection and PaddleOCR for OCR, focusing on PDF and image document analysis. The project facilitates segmentation, extraction, and analysis of document structures.

# Document Table Detection and Structure Recognition

This project focuses on automating the detection and structural analysis of tables within documents. It utilizes YOLOv8X and YOLOv8M models for table detection, along with PaddleOCR for optical character recognition (OCR) tasks. The workflow involves segmenting tables from PDF and image documents, extracting them, and analyzing their structure for further processing.

## Key Features:

- **Table Detection:** YOLOv8X and YOLOv8M models are employed for accurate table detection within documents.
  
- **Optical Character Recognition (OCR):** PaddleOCR is used to extract text content from the detected tables.
  
- **Structural Analysis:** OpenCV algorithms and methods are utilized for analyzing the structure of detected tables, facilitating further data processing.

## Workflow:

1. **Document Processing:** PDF and image documents containing tables are processed.
   
2. **Table Detection:** YOLOv8X and YOLOv8M models detect tables within the documents.
   
3. **Text Extraction:** PaddleOCR extracts text content from the detected tables.
   
4. **Structural Analysis:** OpenCV algorithms analyze the structure of the detected tables for further processing.

## Usage:

1. **Environment Setup:** Ensure that the necessary dependencies, including YOLOv8X, YOLOv8M, PaddleOCR, and OpenCV, are installed.
   
2. **Document Input:** Provide PDF or image documents containing tables for processing.
   
3. **Run Processing Script:** Execute the processing script to detect tables, extract text, and analyze table structures.
   
4. **Output Generation:** Processed documents with annotated tables and extracted text are generated as output.

