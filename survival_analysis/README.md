# 🏥 Survival Analysis: Predicting Risk Over Time

This project replaces traditional **age prediction** with **survival analysis**, modeling the **probability of death over time**.

## **📂 Project Scope**
✅ **Step 1: Frame the problem as survival analysis**
- Instead of predicting **fixed age of death**, model **risk over time**.
- More realistic for **healthcare, insurance, and risk assessment**.

✅ **Step 2: Use Advanced AI Models**
- **DeepSurv (Deep Learning)**
- **XGBoost AFT (Accelerated Failure Time)**
- **TabNet (Neural Network for Tabular Data)**
- **EBM (Explainable Boosting Machine)**
- **LightGBM (Gradient Boosting)**
- **NODE (Neural Oblivious Decision Ensembles)**

✅ **Step 3: Deploy as an API**
- Convert the model into a **FastAPI web service** for real-world use.
- Deploy with **Docker + Google Cloud** for scalability.

## **📊 Model Performance**
| Model | RMSE | MAE |
|--------|------|-----|
| **XGBoost AFT** | 69.8 | 67.8 |
| **TabNet** | 15.7 | 12.4 |
| **EBM** | 15.6 | 12.3 |
| **LightGBM** | 15.6 | 12.3 |
| **NODE** | 36.5 | 27.3 |

## **🔬 Why Survival Analysis?**
- **Old Approach:** Predict **fixed age of death** → inaccurate & unrealistic.
- **New Approach:** Predict **risk of death over time** → practical & useful.

### **Business Analogy**
**Imagine you’re an insurance company:**
- **Old Approach:** "This customer will cancel in 3 years."
- **New Approach:** "This customer has a **20% risk** of canceling in the next year."

**Better for:**  
✔ **Healthcare** (e.g., predicting disease risk over time).  
✔ **Insurance** (e.g., calculating life expectancy dynamically).  
✔ **Finance** (e.g., loan default risk modeling).  

## **🛠️ Tools Used**
- **Deep Learning:** PyTorch, Pycox, DeepSurv
- **Gradient Boosting:** XGBoost, LightGBM
- **Neural Networks:** TabNet, NODE
- **Model Deployment:** FastAPI, Docker, Google Cloud

## **🚀 Next Steps**
- **Improve feature engineering** (e.g., adding socioeconomic factors).
- **Deploy models as APIs** for real-world applications.
