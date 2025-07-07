
# Customer Churn Prediction 📉

Predict whether a customer will churn (leave) or stay, based on their activity and subscription patterns using Machine Learning.

---

## 📁 Dataset
The dataset contains features such as:

- Age  
- Gender  
- Tenure  
- Usage Frequency  
- Support Calls  
- Payment Delay  
- Subscription Type  
- Contract Length  
- Total Spend  
- Last Interaction  
- Churn (Target)

---

## 🧠 Technologies Used
- Python  
- Jupyter Notebook  
- Scikit-Learn  
- Pandas  
- Matplotlib / Seaborn  
- Git + GitHub

---

## 🔎 Steps Performed

1. **Data Cleaning & Preprocessing**  
2. **Label Encoding** for categorical values  
3. **Train-Test Split**  
4. **Model Training** using Logistic Regression  
5. **Model Evaluation** using Accuracy, Classification Report, and Confusion Matrix  
6. **Visualization** using Seaborn heatmap

---

## 📊 Output

### ✅ Accuracy Score:
`0.8281`  
*(The model correctly predicted ~82.8% of customer churn outcomes.)*

---

### 🌀 Confusion Matrix:

|                | Predicted No (0) | Predicted Yes (1) |
|----------------|------------------|-------------------|
| **Actual No (0)**  |     5622         |      1171         |
| **Actual Yes (1)** |     1041         |      5041         |

---


## ✅ How to Run

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
jupyter notebook
