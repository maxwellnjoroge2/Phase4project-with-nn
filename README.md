# Phase4project-with-nn

# Loan Approval Prediction with Neural Network

This project predicts loan approval using borrower information, applying a neural network built with TensorFlow/Keras.

## 📋 Dataset
- `LoanApprovalPrediction.csv`
- Columns include: `Gender`, `Married`, `Education`, `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Credit_History`, `Property_Area`, `Loan_Status` (target).

## 🔷 Project Steps
- Exploratory Data Analysis (EDA)
- Data preprocessing: handling missing values, encoding, scaling.
- Neural Network model:
  - Input: borrower and loan attributes.
  - Output: `Loan_Status` (approved / not approved)
- Evaluation: Accuracy, confusion matrix, classification report.

## 📊 Results
- The neural network achieved reasonable predictive performance.
- Accuracy and validation curves are included in the notebook.

## 🚀 How to Run
1️⃣ Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
```

2️⃣ Run the notebook:
```bash
jupyter notebook Loan_approval_Prediction_with_NN.ipynb
```

## 📁 Files
- `Loan_approval_Prediction_with_NN.ipynb` — full code & results.
- `LoanApprovalPrediction.csv` — dataset.
- `Loan_Approval_Presentation.pptx` — slides.
