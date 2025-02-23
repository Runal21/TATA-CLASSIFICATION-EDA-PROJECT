# 🚀 TATA Classification - Machine Failure Prediction

## 📌 Project Overview
This project aims to predict machine failures based on sensor readings such as **temperature, speed, torque, and tool wear**.  
By analyzing these factors, we help businesses **prevent failures, optimize operations, and reduce maintenance costs**.

## 🗂 Dataset
- **Source:** Industrial machine sensor data
- **Features:**
  - `Air temperature [K]`, `Process temperature [K]`
  - `Rotational speed [rpm]`, `Torque [Nm]`
  - `Tool wear [min]`, `Failure types (TWF, HDF, PWF, OSF, RNF)`

## 🔍 Exploratory Data Analysis (EDA)
- Univariate, Bivariate & Multivariate analysis
- Correlation heatmaps & visualizations
- Failure patterns identification

## ⚙️ Machine Learning Models
- **Feature Engineering**: Scaling, encoding, handling missing values
- **Modeling**: Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

## 📈 Key Insights & Business Impact
- **High temperature & torque increase failure risk** ✅
- **Certain product types have more failures** ❌
- **Speed & Torque have an inverse relationship** 🔄

## 🏗 Future Improvements
- Deploy model using **Flask/FastAPI** for real-time predictions
- Use **deep learning models (LSTMs)** for time-series failure prediction
- Improve failure classification using **ensemble learning**

## 🔧 Setup Instructions
### 1️⃣ Clone Repository
```bash
git clone https://github.com/Runal21/TATA-CLASSIFICATION-EDA-PROJECT.git
cd TATA-CLASSIFICATION-EDA-PROJECT
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run Jupyter Notebook
```bash
jupyter notebook
```

## 🤝 Contributing
Feel free to **fork** the repository and submit a **pull request** for improvements!

## 📩 Contact
For any queries, reach out via [[LinkedIn](https://www.linkedin.com/in/runal-bhosale/)] or [rubhosale21@gmail.com].

