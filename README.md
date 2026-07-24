🛒 Flipkart Customer Service Satisfaction Prediction using Machine Learning
📌 Project Overview

This project aims to predict Customer Satisfaction (CSAT Score) for Flipkart customer support interactions using Machine Learning. By analyzing customer support data, the model helps identify factors that influence customer satisfaction and assists businesses in improving their customer service quality.

🎯 Objective

The main objective of this project is to build a Machine Learning model that predicts the Customer Satisfaction (CSAT Score) based on customer interaction details.

📂 Dataset Information

The dataset contains 85,907 customer support records with 20 features, including:

Channel Name
Category
Sub-category
Customer City
Product Category
Item Price
Connected Handling Time
Tenure Bucket
Agent Shift
CSAT Score (Target Variable)
🛠 Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
📊 Project Workflow
Data Loading
Data Cleaning
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
One-Hot Encoding
Train-Test Split
Decision Tree Classification
Random Forest Classification
Hyperparameter Tuning
Model Evaluation
Performance Comparison
🤖 Machine Learning Models
Decision Tree Classifier
Accuracy: 66.09%
Random Forest Classifier
Accuracy: 56.36%
Tuned Random Forest
Accuracy: 60.16%
📈 Evaluation Metrics

The models were evaluated using:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
📉 Visualizations

The project includes:

CSAT Score Distribution
Missing Value Analysis
Correlation Heatmap
Category-wise Analysis
Product Category Analysis
Feature Importance Graph
Model Performance Comparison
📁 Repository Structure
├── Flipkart.ipynb
├── Customer_support_data.csv
├── Flipkart_Presentation.pptx
├── README.md
▶️ How to Run
Clone this repository.
Open the notebook in Google Colab or Jupyter Notebook.
Install the required libraries.
pip install pandas numpy matplotlib seaborn scikit-learn
Run all notebook cells.
📌 Key Insights
Customer support channel and issue category significantly influence customer satisfaction.
Proper data preprocessing improves model performance.
The Decision Tree model achieved the highest accuracy on this dataset.
🚀 Future Improvements
Apply advanced ensemble methods such as XGBoost or LightGBM.
Perform feature selection to improve prediction accuracy.
Deploy the model using Flask or Streamlit.
Build an interactive dashboard for real-time CSAT prediction.

👩‍💻 Author
Rishika
