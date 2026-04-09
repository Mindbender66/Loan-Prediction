# 🏦 Loan Approval Prediction — ML Classification Project

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Type](https://img.shields.io/badge/Type-Academic%20Project-purple)

A Machine Learning project that predicts whether a loan application should be **approved or rejected** based on applicant details. Built as part of IA-1 Assignment — Team 9.

---

## 👥 Team 9

| Name | Roll No |
|---|---|
| Arpitha Singh | R22DG002 |
| Meruva Sivani | R22DG030 |
| Valmiki Sharath | R22DG061 |
| Nandini V | R22DG032 |

---

## 📁 Project Structure

```
loan-approval-prediction/
│
├── FINAL_CODE.html                  # Main project notebook (HTML export)
├── Logistic_Regression.html         # Logistic Regression notebook
├── macro_project.html               # Full macro-level analysis notebook
├── Pgm_DTC_DTR_RF.pdf               # Decision Tree, Regression & Random Forest code
├── pgm_typesofregression.pdf        # Regression types code (Linear, Ridge, Lasso, KNN)
├── loan_train.csv                   # Training dataset
├── loan_test.csv                    # Testing dataset
├── LoanApprovalDataset.pdf          # Dataset documentation
├── Research_Paper.docx              # Full research paper with literature review
└── README.md
```

---

## 📊 Dataset

| Feature | Description |
|---|---|
| `Gender` | Male / Female |
| `Married` | Applicant married (Y/N) |
| `Dependents` | Number of dependents |
| `Education` | Graduate / Not Graduate |
| `Self_Employed` | Self employed (Y/N) |
| `ApplicantIncome` | Applicant's income |
| `CoapplicantIncome` | Co-applicant's income |
| `LoanAmount` | Loan amount requested |
| `Loan_Amount_Term` | Term of loan in months |
| `Credit_History` | Credit history (1 = good, 0 = bad) |
| `Property_Area` | Urban / Semi-Urban / Rural |
| `Loan_Status` | **Target** — Y = Approved, N = Rejected |

---

## 🤖 Models Used

- **Logistic Regression** — primary model, best accuracy ~81%
- **Decision Tree Classifier** — tree-based classification
- **Decision Tree Regressor** — regression variant
- **Random Forest** — ensemble method with 100 estimators
- **Linear Regression, Ridge, Lasso, KNN Regressor** — regression comparisons

---

## 📈 Key Finding

> **Credit History** is the single most important factor in loan approval. Applicants with a bad credit history are almost always rejected.

---

## ⚙️ Setup & Run

```bash
# Clone the repo
git clone https://github.com/Mindbender66/loan-approval-prediction.git
cd loan-approval-prediction

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Open any notebook HTML or run the .py scripts
```

---

## 📄 Research Paper

A full literature review comparing 10+ existing works on loan approval ML systems is included in `Research_Paper.docx`. Key algorithms reviewed: Logistic Regression, Decision Tree, Random Forest, SVM, XGBoost, Naïve Bayes.

---

## 👤 Author (GitHub)

**Valmiki Sarath**
- GitHub: [@Mindbender66](https://github.com/Mindbender66)
- Email: valmikisarath6666@gmail.com

---

## 📄 License

Open source under the [MIT License](LICENSE).
