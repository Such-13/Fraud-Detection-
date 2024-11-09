# Fraud-Detection-
A minor Project implementing Various Model to identify Frauds .  
# Fraud Detection Projects Repository

This repository contains four Python-based fraud detection projects, each focusing on different machine learning techniques and methodologies to address the increasing threat of financial fraud in online transactions. With the rise of digital finance, fraud detection has become essential to protect both consumers and institutions. These projects demonstrate various approaches to detect fraudulent activities using supervised, ensemble, and deep learning models.

## Projects Overview

### 1. **Decision Tree and Ensemble Techniques for Fraud Detection**
   - **Description**: This project applies traditional machine learning techniques such as Decision Tree, Random Forest, AdaBoost, and Support Vector Machine to classify transactions as fraudulent or non-fraudulent.
   - **Dataset**: The dataset `data.csv` contains features such as transaction time, amount, and location.
   - **Methods Used**: Decision Tree, CNN, Logistic Regression, Random Forest, AdaBoost, SVM, and Bagging Classifier.
   - **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score, and visualization with bar charts.
   - **Imbalance Handling**: SMOTE was applied to balance the dataset.

### 2. **LSTM Autoencoder for Fraud Detection**
   - **Description**: An unsupervised approach utilizing an LSTM-based autoencoder to detect anomalies in transaction data, designed for cases where labels may not be available.
   - **Dataset**: `fraudTest.csv`, containing transaction information with a fraud label (`is_fraud`) and attributes like transaction amount and timestamp.
   - **Methods Used**: LSTM architecture to learn and reconstruct patterns in normal transactions, detecting fraud as anomalies.
   - **Imbalance Handling**: SMOTE-ENN was used for data balancing.
   - **Evaluation Metrics**: Accuracy, ROC AUC Score, with high precision metrics displayed to 15 decimal places.

### 3. **Logistic Regression and SVM for Fraud Detection**
   - **Description**: This project explores logistic regression and support vector machines (SVM) to classify fraud, targeting models with interpretability and efficiency.
   - **Dataset**: A credit card transactions dataset (`fraud.csv`), with features such as transaction amount, timestamp, and customer demographics.
   - **Methods Used**: Logistic Regression and SVM, both optimized and tuned for balanced performance.
   - **Evaluation Metrics**: Accuracy, Precision, and Confusion Matrix to evaluate classification performance.



## Repository Structure
```plaintext
├── Project 1 - LR,SVM,DT,RF models without SMOTE
│   ├── data.csv
│   ├── 3 models without SMOTE.py
├── Project 2 -  LR,DT,RF models with SMOTE
│   ├── fraudTest.csv
│   ├── 3 models with SMOTE.py
├── Project 3 -CNN model
│   ├── fraud.csv
│   ├── CNN model.py
├── Project 4 -LSTM Model
│   ├── fraud.csv
│   ├── LSTM Model.py
├── README.md

```
## Requirements

- **Python**: 3.8 or higher
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `imblearn`, `tensorflow`, `keras`, `matplotlib`, `seaborn`
- **Installation**:
  ```bash
  pip install -r requirements.txt
```
## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/yourusername/fraud-detection-projects.git
```
# Usage

To run the associated Python script for each project, navigate to the desired project folder and execute the script. Ensure that the dataset is in the correct format and location as specified in  project's README.

## Running the Script

Each project contains its own README with specific instructions on running the scripts and understanding the model outputs. Simply navigate to a project directory and execute the script as follows:

```bash
python <script_name>.py
```
## Contributions
Contributions are welcome! Please feel free to submit pull requests for improvements or open issues to discuss potential changes.

## License
This repository is licensed under the MIT License.

These projects aim to provide insights into different machine learning approaches for fraud detection, helping to build systems that can more effectively identify and prevent fraudulent activity in financial systems.





