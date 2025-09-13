# 📦 E-Commerce Product Delivery Prediction

This project predicts whether products from an international e-commerce company will be delivered on time or not.  
It also explores key factors influencing delivery and customer behavior.

---

## 📊 Dataset
- **Rows:** 10,999
- **Columns:** 12
- **Target Variable:** `Reached.on.Time_Y.N`  
  - 0 → On time  
  - 1 → Delayed  

---

## ⚙️ Project Workflow
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Building (Logistic Regression, Decision Tree, Random Forest, KNN)
5. Model Evaluation (Accuracy, F1, Confusion Matrix, ROC-AUC)
6. Saving Pipelines with `joblib`
7. Insights & Conclusion

---

## 🏆 Results
- **Best Model:** Decision Tree (69% accuracy)
- Random Forest: 68%
- Logistic Regression: 67%
- KNN: 65%

---

## 📌 Key Insights
- Products weighing **2500–3500g** and costing **< $250** were more likely to be delivered on time.
- More **customer care calls → higher chance of delay**.
- Loyal customers with **more prior purchases → more timely deliveries**.
- Discounts **>10% improved delivery timeliness**.

---

## 🚀 How to Run
```bash
# Clone repo
git clone https://github.com/<your-username>/Ecommerce-Delivery-Prediction.git
cd Ecommerce-Delivery-Prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook notebooks/EDA_Modeling.ipynb
