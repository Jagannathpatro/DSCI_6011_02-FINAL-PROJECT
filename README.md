# DSCI_6011_02-FINAL-PROJECT by Sravya Kaitha, Jagannath Patro Allupati and Narsi Reddy Sanivarapu
# Project :Enhanced Customer Experience: Product Complaints Identification

## Project Overview
This project utilizes Natural Language Processing (NLP) techniques to automatically identify and categorize customer product complaints from textual data. The goal is to enhance customer service efficiency by automating the complaint handling process.

### Features
- **Complaint Detection**: Automatically detect complaint texts from customer feedback.
- **Classification**: Categorize complaints into predefined categories based on content.

## Getting Started

### Prerequisites
- Google Colab Notebook

### Installation
Clone the repository to your local machine:
git clone repository url
Upload the downloaded project to Google Colab
Download the dataset from https://github.com/halpert3/complaint-content-classification-nlp/blob/main/project_data/complaints_processed.csv
In Google Drive, upload the downloaded dataset
Run the notebook

## Conclusion
Using Natural Language Processing (NLP) to identify product complaints improves the customer experience dramatically. NLP approaches simplify the processing of massive volumes of consumer input, allowing firms to handle issues quickly and accurately. Businesses may use sentiment analysis, topic modeling, and machine learning classifiers to identify complaints and prioritize resolution efforts properly. The continuous modification of NLP models guarantees that complaint identification and customer satisfaction continue to increase. This project leverages the use of two models (Bi-LSTM and DistilBERT from Hugging Face). From the analysis conducted, Bi-LSTM outperforms DistilBERT as it achieves a higher average f1 score of 0.87 compared to 0.72 of DistilBERT.
