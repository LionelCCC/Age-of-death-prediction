# 📊 Age Prediction: Machine Learning & Deep Learning Models

This project explored various **machine learning and deep learning models** to predict **age of death** based on demographic and clinical features.

## **📂 Project Structure**
Each notebook applies a different model to estimate age based on structured data.

| Model  | Type | Purpose |
|--------|------|---------|
| **XGBoost** | Gradient Boosting | Baseline structured data model |
| **TabNet** | Neural Network | Deep learning for tabular data |
| **DF2M** | Bayesian Factor Model | Probabilistic modeling |
| **MOIRAI** | Transformer Model | Pre-trained time-series forecasting |

## **📊 Model Performance**
| Model  | RMSE | MAE | R² Score |
|--------|------|-----|----------|
| **XGBoost** | 21.34 | 18.04 | -0.639 |
| **TabNet**  | 0.53 (Best Epoch) | - | - |
| **DF2M** | Results unclear | - | - |

## **⚠️ Limitations**
❌ Ignores **censored individuals** (people still alive).  
❌ **Assumes all observed ages are final**, which is unrealistic.  
❌ **Not useful for real-world risk modeling** (e.g., healthcare, insurance).  

## **🔄 Transition to Survival Analysis**
To overcome these limitations, we have **pivoted to survival analysis**, which:
- Predicts **probability of death over time**, rather than a fixed age.
- Handles **incomplete data** (people still alive).
- Is **more practical for real-world applications** (e.g., healthcare planning).

🚀 **See the [Survival Analysis README](../Survival_Analysis_README.md) for details.**
