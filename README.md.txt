# Fraud Detection & Risk Analysis (PaySim)

Problem Statement

Detect fraudulent financial transactions and analyze patterns to reduce financial loss.

---

Dataset

* PaySim synthetic financial dataset
* Contains transaction details such as type, amount, and balances

---

Key Insights

* Fraud is highly imbalanced (~0.13%)
* Fraud mainly occurs in TRANSFER and CASH_OUT transactions
* Transaction amount alone is not a strong indicator
* Balance inconsistencies strongly indicate fraud

---

Model

* Logistic Regression
* Features used:

  * amount
  * errorOrig
  * errorDest

---

Results

* Initial Recall: 43%
* Improved Recall: 85% (after handling class imbalance)

---

Risk Scoring System

Transactions categorized into:

* Low Risk
* Medium Risk
* High Risk

---

Conclusion

The system successfully identifies fraudulent transactions and prioritizes them based on risk level, helping improve fraud detection efficiency.

---

Tools Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
