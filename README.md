# Document Classification and OCR Project

## Overview

This project is divided into three main phases, each aimed at streamlining document processing and information extraction. Our goal is to create a robust system for working with scanned documents, enabling us to identify document types, convert images to editable text using Optical Character Recognition (OCR), and extract key information entities.

## Phases

### 1. Document Classification

In the first phase, we focus on developing a document classification model. This model's primary objective is to determine the type of document from scanned images. Identifying the document type is crucial as it helps us determine the appropriate processing and further actions.  To achieve this, we have utilized LayoutLMv3ForSequenceClassification, a state-of-the-art model for document layout analysis and document type identification.

### 2. Optical Character Recognition (OCR)

In the second phase, we implement OCR technology to convert scanned document images into machine-readable and editable text. This step is essential for making the content of the documents accessible and manipulable. 

### 3. Information Entity Extraction

The final phase focuses on identifying and extracting key information entities from the documents. By recognizing specific data points, such as names, dates, addresses, and more, we can automatically gather and store crucial information from the documents. This process simplifies data entry and retrieval for various applications.

