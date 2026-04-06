🏦 Loan Default Prediction using Machine Learning

📌 Project Overview

This project aims to predict whether a loan application will be **Approved or Rejected** based on applicant details.
It uses a **Machine Learning model (Random Forest Classifier)** trained on financial and personal attributes.

The model also provides a **default risk probability**, helping in better decision-making.

 🎯 Objectives

* Predict loan approval status
* Estimate **default probability (risk level)**
* Understand how financial factors affect loan decisions

📊 Features Used

The model is trained using the following input features:

1. Number of Dependents
2. Education (Graduate / Not Graduate)
3. Self Employed (Yes / No)
4. Annual Income
5. Loan Amount
6. Loan Term
7. Credit History (Yes / No)
8. CIBIL Score
9. Residential Assets Value
10. Commercial Assets Value
11. Luxury Assets Value
12. Bank Balance

🧠 Machine Learning Model

* Algorithm: **Random Forest Classifier**
* Library: `scikit-learn`
* Task: Binary Classification (Approved / Rejected)

⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab

🚀 How to Run (Google Colab)

1. Open Google Colab
2. Upload the notebook or paste the training code
3. Run all cells
4. The model will be trained and saved as:

```
loan_model.pkl
```

---

💾 Model Saving

The trained model is saved using `pickle`:

```python
import pickle
pickle.dump(model, open('loan_model.pkl', 'wb'))
```

---

📈 Prediction Example

Example Input:

```
Dependents: 1
Education: Graduate
Self Employed: No
Income: 70000
Loan Amount: 20000
Loan Term: 12
Credit History: Yes
CIBIL Score: 500
Residential Assets: 400000
Commercial Assets: 0
Luxury Assets: 0
Bank Balance: 80000
```

Output:

```
Loan Rejected ❌
Default Probability: 0.87
High Risk Customer 🔴
```

📊 Model Output

* **Loan Status** → Approved / Rejected
* **Default Probability** → Value between 0 and 1
* **Risk Level**:

  * Low Risk 🟢
  * Medium Risk 🟡
  * High Risk 🔴

 📌 Future Improvements

* Use real-world dataset for better accuracy
* Feature engineering and scaling
* Hyperparameter tuning
* Deploy as a web application

👩‍💻 Author

Janaranjani S

⭐ GitHub

If you found this project useful, consider giving it a ⭐!
