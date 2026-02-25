# Insurance OCR Classification

<p align="center">
  <img src="Insurance%20Document%20OCR%20Classification.png" alt="Insurance Document OCR Classification">
</p>

## Overview
This project aims to build an Optical Character Recognition (OCR) system specifically designed for classifying insurance documents. The system utilizes machine learning techniques to accurately extract and classify information from scanned documents.

## Objectives
- To develop an OCR system capable of reading and classifying insurance documents.
- To enhance data accessibility and reduce manual data entry time.
- To achieve high accuracy in classifying different types of insurance documents.

## Technologies
- Python
- TensorFlow/Keras
- OpenCV
- Scikit-learn
- Pandas
- NumPy

## Dataset Information
The dataset consists of scanned images of various insurance documents, along with their labeled categories. The images are pre-processed to improve OCR accuracy. The dataset details include:
- Number of images: 5,000
- Document types: Policy documents, Claim forms, etc.

## ML Approach
1. **Data Collection:** Gather images of insurance documents.
2. **Data Preprocessing:** Use OpenCV for image processing to enhance readability.
3. **Model Training:** Train a convolutional neural network (CNN) using TensorFlow/Keras.
4. **Validation:** Validate the model using a separate test dataset to assess accuracy.
5. **Deployment:** Use Flask to create a simple web application for end-users.

## Project Structure
```
insurance-ocr-classification
│
├── notebook.ipynb
├── ocr_insurance_dataset.pkl
├── README.md
└── requirements.txt
```

### notebook.ipynb
Contains the full machine learning workflow including preprocessing, training, and evaluation.

### ocr_insurance_dataset.pkl
Serialized dataset used for training the model.

### requirements.txt
List of required Python libraries.

## How to Run Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Abdelrahmannasser139/insurance-ocr-classification.git
   cd insurance-ocr-classification
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Applications
- Automated insurance claims processing
- Document management systems
- Data extraction for analytics and reporting

## Improvements
- Implement additional document types for classification.
- Enhance OCR accuracy with more sophisticated models.
- Introduce user authentication in the web application.

## Learning Outcomes
- Understanding of OCR technology and its applications.
- Experience in building machine learning models and deploying them as web applications.

## Author Information
- **Name:** Abdelrahman Nasser
- **Email:** Abdelrahmannasser139@gmail.com
## Author Information
- **Name:** Abdelrahman Nasser
- **Email:** Abdelrahmannasser139@gmail.com
