# Age Prediction Modeling: A Multi-Model Exploration

## Overview
This repository is a **showcase of Lionel’s machine learning and modeling skills**, applying **various predictive models** to the same dataset to explore their effectiveness. Each model is implemented in a **dedicated notebook**, making it easy to compare methodologies and their impact on predictive performance.

### **Project Structure**
Each notebook in this repository covers a different model and its application to the dataset. The goal is to:
- **Experiment with different modeling techniques**.
- **Compare performance across models**.
- **Understand the strengths and weaknesses of each approach**.

### **Implemented Models**
| Model  | Type | Notebook | Purpose |
|--------|------|----------|----------|
| **XGBoost** | Gradient Boosting | `XGBoost_AgePrediction.ipynb` | Benchmark model for structured data |
| **TabNet** | Neural Network | `TabNet_AgePrediction.ipynb` | Deep learning model designed for tabular data |
| **DF2M** | Bayesian Factor Model | `DF2M_AgePrediction.ipynb` | Probabilistic modeling with deep kernels |
| **MOIRAI** | Transformer for Time Series | `MOIRAI_AgePrediction.ipynb` | Large-scale pre-trained forecasting model |
| **More to come...** | TBD | `FutureModels.ipynb` | Exploring additional methods |

### **Dataset**
The dataset used in this project includes:
- **Demographic features** (e.g., gender, country, occupation).
- **Temporal attributes** (e.g., birth year, death year).
- **Text-based descriptions** that can be transformed into structured inputs.

Each model may be used for different types of predictions:
- **Regression**: Predicting the **year of death**.
- **Classification**: Predicting the **manner of death** or other categorical variables.

### **Why Separate Notebooks?**
Each notebook is **dedicated to one model** to ensure clarity and focus. This allows for:
- **A deep dive into each modeling approach**.
- **More modular comparisons** between models.
- **Easier scalability** as new models are added to the repository.

### **Next Steps**
✅ Implement additional models to expand the repository.  
✅ Evaluate model performances systematically.  
✅ Share insights on which models work best for different tasks.  

🚀 Stay tuned for updates and new model implementations!
