# Category Encoding using Pandas 🐼

## 📌 Task Overview
This project is part of the **μLearn Data Science Interest Group** tasks.
The goal is to perform **Category Encoding** on a dataset using only **Pandas** — converting categorical values into numerical ones suitable for Machine Learning.

---

## 🎯 Objectives
- Load and explore the dataset using Pandas
- Identify all categorical columns
- Apply suitable encoding techniques using only Pandas
- Save the cleaned/encoded dataset

---

## 🛠️ Encoding Techniques Used
- **Label Encoding** — using `.astype('category').cat.codes`
- **One-Hot Encoding** — using `pd.get_dummies()`

---

## 📁 Repository Structure

```
├── preprocessing.py       # Main encoding script
├── dataset.csv            # Original dataset
├── cleaned_dataset.csv    # Encoded/cleaned dataset
└── README.md              # Project documentation
```
---

## 📊 Results
- Identified and encoded all categorical columns
- Dataset is now fully numerical and ready for ML models

---

## 🙌 Acknowledgements
- [μLearn Foundation](https://mulearn.org)
- Data Science Interest Group
