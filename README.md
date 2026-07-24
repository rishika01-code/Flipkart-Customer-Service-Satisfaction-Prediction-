# 🛒 Flipkart Customer Service Satisfaction Prediction using Machine Learning

A Machine Learning project to predict **Flipkart Customer Satisfaction (CSAT Score)** using customer support interaction data. This project applies data preprocessing, exploratory data analysis (EDA), feature engineering, and classification models to analyze customer satisfaction and identify the most influential factors affecting CSAT scores.

---

## 📌 Project Overview

Customer satisfaction is one of the most important metrics for any e-commerce platform. This project predicts the **Customer Satisfaction (CSAT Score)** using customer support data collected from Flipkart.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Machine Learning Model Building
- Hyperparameter Tuning
- Model Evaluation

---

## 🎯 Objective

The objective of this project is to build a Machine Learning model that predicts the **Customer Satisfaction (CSAT Score)** based on customer support interactions and service-related features.

---

## 📂 Dataset

- **Dataset:** Flipkart Customer Support Dataset
- **Total Records:** 85,907
- **Features:** 20

### Important Features

- Channel Name
- Category
- Sub-category
- Customer City
- Product Category
- Item Price
- Connected Handling Time
- Tenure Bucket
- Agent Shift
- CSAT Score (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Feature Engineering
6. One-Hot Encoding
7. Train-Test Split
8. Decision Tree Model
9. Random Forest Model
10. Hyperparameter Tuning
11. Model Evaluation
12. Performance Comparison

---

## 🤖 Machine Learning Models

| Model | Accuracy |
|--------|----------|
| Decision Tree | **66.09%** |
| Random Forest | **56.36%** |
| Tuned Random Forest | **60.16%** |

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📉 Data Visualizations

The project includes:

- Missing Value Analysis
- CSAT Score Distribution
- Category-wise Analysis
- Product Category Analysis
- Boxplots
- Feature Importance
- Confusion Matrix
- Model Performance Comparison

---

## 📁 Repository Structure

```text
Flipkart-Customer-Service-Satisfaction-Prediction/
│
├── Flipkart.ipynb
├── Customer_support_data.csv
├── Flipkart_Presentation.pptx
├── README.md
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/rishika01-code/Flipkart-Customer-Service-Satisfaction-Prediction.git
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run the Notebook

Open **Flipkart.ipynb** in Google Colab or Jupyter Notebook and run all cells.

---

## 📌 Key Insights

- Customer support channel influences customer satisfaction.
- Service category impacts CSAT scores.
- Proper preprocessing improves model performance.
- Decision Tree achieved the highest accuracy for this dataset.

---

## 🚀 Future Improvements

- Implement XGBoost and LightGBM models.
- Perform advanced feature selection.
- Deploy the model using Streamlit or Flask.
- Build a real-time customer satisfaction prediction dashboard.

---

## 👩‍💻 Author

**Rishika**


---

## ⭐ Support

If you found this project helpful, please consider **starring ⭐ this repository**.
