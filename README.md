
## Portuguese Bank Term Deposit Prediction

### 📌 Project Overview
This project predicts whether a bank customer will subscribe to a term deposit based on marketing campaign data from a Portuguese bank. The goal is to help the bank target customers more effectively.

### 📊 Dataset Information
- **File used**: `bank-additional-full.csv`
- **Target variable**: `y` → yes/no (subscription)
- **Features**: Demographic details, job, marital status, loans, contact method, economic indicators.

### 🛠 Steps in the Project
1. Data Understanding & Cleaning
2. Handling Missing Values
3. Encoding Categorical Variables
4. Feature Scaling
5. Feature Selection (Chi2 & ANOVA)
6. Handling Class Imbalance (SMOTE)
7. Train/Test Split
8. Model Training (Logistic Regression, Decision Tree, Random Forest, XGBoost, LightGBM)
9. Model Evaluation & Comparison
10. Best Model Selection
11. Save Model for Deployment
12. Marketing Recommendations
13. Challenges & Solutions

### 📈 Results
- **Best Model**: Random Forest
- **Accuracy**: ~91%
- **ROC-AUC**: ~96%
- **Key Insight**: Retired, management, and higher-educated customers have higher subscription rates.

### 📦 Requirements
Install dependencies:
```bash
pip install -r requirements.txt
```

### 📤 How to Run
```bash
git clone https://github.com/<your-username>/Portuguese_Bank_Term_Deposit_Prediction.git
cd Portuguese_Bank_Term_Deposit_Prediction
pip install -r requirements.txt
jupyter notebook Portuguese_Bank_Term_Deposit_Prediction.ipynb
```

### 📌 Author
Developed as part of a Machine Learning project for bank marketing campaign prediction.

---