# Loan Approval Prediction

This project predicts whether a loan will be approved based on applicant details using **Machine Learning models**.

---

## Files Included
- `Loan_prediction.ipynb` → Main Jupyter Notebook containing preprocessing, training, and predictions.
- `loan.csv` → Dataset used for training/testing.
- `requirements.txt` → Python dependencies (install using `pip install -r requirements.txt`).
- `.gitignore` → To avoid uploading unnecessary files.

---

## Features
- Algorithms used: **Decision Tree, Random Forest, AdaBoost**
- Evaluation Metrics: **MAE, RMSE, R²**
- Input Features: Gender, Marital Status, Dependents, Education, Income, Loan Amount, etc.
- Output: **Loan Approved** or **Loan Not Approved**

---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/Loan-Prediction-Project.git
   cd Loan-Prediction-Project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Loan_prediction.ipynb
   ```

---

## Example Input
```python
{
    'Gender': 1,
    'Married': 1,
    'Dependents': 0,
    'Education': 0,
    'Self_Employed': 0,
    'ApplicantIncome': 5000,
    'CoapplicantIncome': 2000,
    'LoanAmount': 150,
    'Loan_Amount_Term': 360,
    'Credit_History': 1.0,
    'Property_Area': 2
}
```

**Output:**  
```
Loan Approved
```

---

## Author
**Hamsa Priya H S**  
B.Tech in Computer Science & Engineering  
Mangalore, Karnataka
