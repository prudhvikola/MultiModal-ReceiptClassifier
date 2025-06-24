# AutoRecClass: Automated Receipt Classification using CV, NLP, and ML

This project focuses on classifying receipt images into predefined categories using a combination of **Computer Vision**, **Natural Language Processing**, and **Machine Learning** techniques. The goal is to assist in automating expense tracking and digital bookkeeping through intelligent categorization of receipts.

## 📁 Project Contents

- `AutoRecClass.ipynb`: Main Jupyter notebook containing the full pipeline from image preprocessing to classification and evaluation.
- `sample_receipts/`: Folder containing example receipt images.
- `models/`: Pre-trained or saved models (optional).
- `requirements.txt`: Python dependencies for running the notebook.

## ⚙️ Features

- Image preprocessing using OpenCV
- OCR-based text extraction using Tesseract
- Text preprocessing and feature extraction (NLTK, TF-IDF)
- Visual feature extraction (edges, contours)
- Classification using ML models (SVM, Random Forest, etc.)
- Evaluation metrics: accuracy, precision, recall, F1-score
- Visualization of results and confusion matrix

## 📌 Technologies Used

- Python
- OpenCV
- Tesseract OCR
- NLTK
- Scikit-learn
- TensorFlow / Keras (optional for deep models)
- Pandas, NumPy
- Matplotlib, Seaborn

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AutoRecClass.git
   cd AutoRecClass
