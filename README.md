# Document Classification and OCR Project


>  ## Overview

This project is divided into three main phases, each aimed at streamlining document processing and information extraction. Our goal is to create a robust system for working with scanned documents, enabling us to identify document types, convert images to editable text using Optical Character Recognition (OCR), and extract key information entities.

>  ## Phases

### 1. Document Classification

In the first phase, we focus on developing a document classification model. This model's primary objective is to determine the type of document from scanned images. Identifying the document type is crucial as it helps us determine the appropriate processing and further actions.  To achieve this, we have utilized LayoutLMv3ForSequenceClassification, a state-of-the-art model for document layout analysis and document type identification.

### 2. Optical Character Recognition (OCR)

In the second phase, we implement OCR technology to convert scanned document images into machine-readable and editable text. This step is essential for making the content of the documents accessible and manipulable. 

### 3. Information Entity Extraction

The final phase focuses on identifying and extracting key information entities from the documents. By recognizing specific data points, such as names, dates, addresses, and more, we can automatically gather and store crucial information from the documents. This process simplifies data entry and retrieval for various applications.

>  ## Data

For training the document processing and information extraction model, we utilized the following datasets:

1. **SROIE (Scanned Receipt OCR and Information Extraction)**: The SROIE dataset is a valuable resource for text recognition from structured and semi-structured scanned receipts. It was created for the SROIE competition held during the ICDAR conference in 2019. This dataset comprises 1000 images, each of which is accompanied by annotations specifying the information to be extracted from the receipt.

2. **FUNSD (Form Understanding in Noisy Scanned Documents)**: The FUNSD dataset is designed for form understanding, optical character recognition, and spatial layout analysis. It consists of 199 fully annotated, noisy scanned forms, each represented as a list of interconnected semantic entities, with information about words, labels, and coordinates.

>  ## Requirements

Before you begin, make sure you meet the following software and hardware requirements to run this project effectively:

- **Python**: We recommend using Python 3.7 or higher.

- **Python Libraries**: 

- **Transformers**:  We recommend using transformers==4.28.0.

- **EasyOCR**: Ensure that you have EasyOCR installed for the OCR phase;

> ## Web Deployment

To make our model available on the internet, we've employed :

1. **Flask**: to serve the document processing model.

2. **ngrok**: To make the Flask web application accessible over the internet, we use ngrok. Ngrok allows us to expose a local server to a public URL, making it easy to share and access the application.




