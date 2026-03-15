# DeepCSAT: E-commerce Customer Satisfaction Prediction using Deep Learning and NLP

## Project Overview
DeepCSAT is an end-to-end Machine Learning and Natural Language Processing (NLP) project designed to analyze customer support interaction data and predict Customer Satisfaction Scores (CSAT).

The system processes customer service information such as response times, issue categories, support channels, and customer remarks to generate predictive insights about customer satisfaction.

This project also includes a **Streamlit web application** that allows users to input service interaction details and obtain predicted CSAT scores.

---

## Project Objectives

- Predict Customer Satisfaction Scores (CSAT) using Machine Learning.
- Analyze customer support performance metrics.
- Apply NLP techniques to identify complaint patterns in customer feedback.
- Build an interactive Streamlit application for predictions.
- Deploy the application for real-time usage.

---

## Dataset Description

The dataset contains customer support interaction records including issue reporting times, response times, agent information, and customer feedback.

### Key Features

- **Unique ID** – Identifier for each interaction  
- **Channel Name** – Support channel used (Chat, Email, Phone)  
- **Category / Sub-category** – Type of issue reported  
- **Customer Remarks** – Text feedback provided by customers  
- **Order ID** – Order reference number  
- **Order Date Time** – Timestamp when the order was placed  
- **Issue Reported At** – Time when the issue was reported  
- **Issue Responded** – Time when the support agent responded  
- **Survey Response Date** – Date when customer feedback was submitted  
- **Customer City** – Location of the customer  
- **Product Category** – Category of product involved in the issue  
- **Item Price** – Price of the purchased item  
- **Connected Handling Time** – Duration of support interaction  
- **Agent Name** – Support agent handling the issue  
- **Supervisor / Manager** – Support team hierarchy  
- **Tenure Bucket** – Experience level of the support agent  
- **Agent Shift** – Work shift of the support agent  
- **CSAT Score** – Customer satisfaction rating  

---

## Feature Engineering

Additional features were created to improve model performance.

### Response Time
Time taken by the support agent to respond to a reported issue.

### Survey Delay
Time difference between issue resolution and survey feedback submission.

### Order to Issue Time
Time between order placement and issue reporting.

---

## Machine Learning Pipeline

The following steps were implemented in the machine learning workflow:

1. Data Cleaning and Preprocessing  
2. Handling Missing Values  
3. Feature Engineering  
4. Encoding Categorical Variables  
5. Train-Test Split  
6. Feature Scaling  
7. Model Training  
8. Model Evaluation  

---

## NLP-Based Complaint Clustering

Customer remarks were analyzed using Natural Language Processing.

Steps performed:

- Text preprocessing
- TF-IDF vectorization
- K-Means clustering

This helps identify common complaint patterns in customer feedback.

---

## Streamlit Web Application

An interactive web application was built using **Streamlit** that allows users to:

- Enter customer service interaction details
- Predict customer satisfaction scores
- Analyze support performance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (TF-IDF, KMeans)
- Matplotlib
- Seaborn
- Streamlit
- Google Colab
- GitHub

---

## Project Structure

```
DeepCSAT_Project
│
├── app.py
├── dataset.csv
├── model.pkl
├── scaler.pkl
├── requirements.txt
├── README.md
└── csat_project_report.pdf
```

---

## Deployment

The Streamlit application can be deployed using:

- Streamlit Community Cloud
- Google Colab with ngrok

---

## Business Use Cases

- Customer satisfaction prediction
- Customer support performance analysis
- Complaint pattern identification
- Customer experience improvement
- Business decision support

---

## Author

**Dharminder Singh Virk**

Technology Stack:  
Python | Machine Learning | NLP | Streamlit
