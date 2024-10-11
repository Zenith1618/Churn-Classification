# 📊 Churn Project

This project tackles two main tasks:  
1. **Churn Classification**: Predicting whether a customer will churn using historical customer data.  
2. **Salary Prediction**: Building a regression model to predict customer salary based on the provided features.

## 💡 Info
- **Data Preprocessing & Classification ANN**: Checkout `experiments.ipynb`.
- **Regression ANN**: Checkout `salaryRegression.ipynb`.
- **Models**: Includes Classification (`model.h5`) and regression model (`regression_model.h5`).
- **Hyperparameter Tuning**: Explored in `hyperparametertuning.ipynb`.
- **Deployment**: Implemented using Streamlit (`app.py`) and (`regression_app.py`).

## 🛠️ Tech Stack
- Python
- Streamlit
- TensorFlow

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Zenith1618/Churn-Classification.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app(for regression use regression_app.py):
   ```bash
   streamlit run app.py
   ```
