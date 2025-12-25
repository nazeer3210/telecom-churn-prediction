\# Telecom Churn Prediction



This project focuses on predicting customer churn in the telecommunication sector using big data processing and machine learning techniques. The goal is to identify customers who are likely to discontinue services, enabling businesses to take proactive retention measures.



The project was developed as part of an \*\*Introduction to Big Data and Data Science\*\* course and is structured to reflect real-world data science workflows.



---



\## Problem Statement



Customer churn is a major challenge in the telecom industry, leading to revenue loss and increased customer acquisition costs.  

This project aims to build a predictive model that accurately classifies whether a customer is likely to churn based on historical usage and service-related features.



---



\## Dataset



\- Telecom customer data containing:

&nbsp; - Customer demographics

&nbsp; - Service usage information

&nbsp; - Contract and billing details

\- Target variable: \*\*Churn (Yes / No)\*\*



---



\## Technologies Used



\### Programming \& Environment

\- Python

\- Google Colab



\### Big Data Processing

\- Apache Spark (PySpark)

\- Spark SQL

\- DataFrames



\### Feature Engineering

\- StringIndexer

\- OneHotEncoder

\- VectorAssembler

\- StandardScaler

\- MinMaxScaler

\- Polynomial Expansion



\### Machine Learning

\- Spark MLlib

\- Random Forest Classifier

\- ML Pipelines

\- Hyperparameter tuning using:

&nbsp; - ParamGridBuilder

&nbsp; - CrossValidator



\### Model Evaluation

\- BinaryClassificationEvaluator

\- MulticlassClassificationEvaluator

\- ROC Curve

\- Precision–Recall Curve



\### Visualization

\- Matplotlib

\- Seaborn

\- Pandas

\- NumPy



---



\## Methodology



1\. Data ingestion and preprocessing using PySpark

2\. Handling categorical and numerical features through encoding and scaling

3\. Building an end-to-end ML pipeline

4\. Training a Random Forest classification model

5\. Hyperparameter tuning with cross-validation

6\. Model evaluation using multiple performance metrics



---



\## Results



\- The trained Random Forest model achieved strong predictive performance.

\- Evaluation metrics such as accuracy, ROC curve, and precision–recall curve indicate effective churn classification.

\- The project demonstrates the scalability and efficiency of Spark-based machine learning pipelines.



---



\## How to Run



This project was developed in \*\*Google Colab\*\*.



1\. Upload the notebook to Google Colab

2\. Ensure Spark is available in the environment

3\. Run the notebook cells sequentially



---



\## Key Learnings



\- Practical application of Apache Spark for large-scale data processing

\- Building scalable machine learning pipelines

\- Performing feature engineering and hyperparameter tuning

\- Evaluating classification models using industry-standard metrics



---



\## Project Context



This project was completed for academic purposes and demonstrates hands-on experience with \*\*Big Data processing and Machine Learning using Apache Spark\*\*.



