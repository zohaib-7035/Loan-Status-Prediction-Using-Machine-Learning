
## **Loan Status Prediction Model 🚀**  

This project predicts **loan approval status** based on customer details using **Machine Learning (SVM Classifier)**.  

### **📌 Features:**  
- Data preprocessing (handling missing values, encoding categorical data).  
- Data visualization using **Seaborn**.  
- Training an **SVM model** for classification.  
- Evaluating model accuracy.  
- Making predictions on new loan applications.  

---

---


Open **Loan_Status_Model.ipynb** in Jupyter Notebook or Google Colab and execute the cells.

---

### **📊 Dataset Details**  
The dataset contains the following features:  
- `Loan_ID` - Unique Loan Identifier  
- `Gender` - Male / Female  
- `Married` - Yes / No  
- `Dependents` - Number of dependents  
- `Education` - Graduate / Not Graduate  
- `Self_Employed` - Yes / No  
- `ApplicantIncome` - Applicant’s Income  
- `CoapplicantIncome` - Co-Applicant’s Income  
- `LoanAmount` - Loan Amount in thousands  
- `Loan_Amount_Term` - Loan Term in months  
- `Credit_History` - Credit history (1 = Yes, 0 = No)  
- `Property_Area` - Rural / Semiurban / Urban  
- `Loan_Status` - **Target Variable (Y = Approved, N = Not Approved)**  

---

### **📌 Model Used**  
- **Support Vector Machine (SVM)** with a **linear kernel**  

**Performance Metrics:**  
- Training Accuracy: **~X%**  
- Testing Accuracy: **~Y%**  

---

### **🚀 Usage**  
If you want to predict a new loan application:  

```python
import numpy as np
new_data = np.array([[1, 1, 0, 5000, 2000, 150, 360, 1, 2]])
new_data = new_data.reshape(1, -1)
prediction = classifier.predict(new_data)

if prediction[0] == 1:
    print("Loan Approved ✅")
else:
    print("Loan Not Approved ❌")
```

---

