✈ Airline Delay Root-Cause Analysis

This project analyzes large-scale U.S. airline operational data to identify and understand the key factors contributing to flight delays.
Rather than focusing solely on prediction, the project emphasizes root-cause analysis, airport behavior patterns, and operational insights using machine learning techniques.

📌 Project Objectives

Examine operational, weather, and system-level contributors to flight delays

Predict arrival delay magnitude using regression modeling

Classify flights as delayed or non-delayed based on operational thresholds

Identify airport-level behavioral patterns using clustering

Apply dimensionality reduction (PCA) to analyze correlated delay components

📊 Dataset

Source: U.S. Department of Transportation (via Kaggle)

Dataset: Commercial Airline Flight Records

Size: Large-scale operational dataset (>500MB)

⚠ Due to file size limitations, the dataset is not included in this repository.

You can download it from:
https://www.kaggle.com/datasets/usdot/flight-delays

After downloading, place flights.csv in the project root directory before running the notebook.

🧠 Methodology
1️⃣ Data Preprocessing

Removed cancelled and incomplete records

Handled missing values in delay components

Engineered classification target (IS_DELAYED)

2️⃣ Exploratory Data Analysis

Visualized delay contribution by cause

Analyzed delay trends across days of the week

3️⃣ Supervised Learning

Linear Regression to estimate arrival delay magnitude

Logistic Regression & Decision Tree to classify delayed flights

Evaluated using MAE, RMSE, R², Accuracy, F1 Score, and Confusion Matrix

4️⃣ Unsupervised Learning

K-Means Clustering to group airports based on delay behavior

Cluster-level analysis for operational pattern discovery

5️⃣ Dimensionality Reduction

Principal Component Analysis (PCA) to reduce correlated delay features and improve interpretability

🛠 Tools & Technologies

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🔍 Key Insights

Airline and air system delays are dominant contributors to overall arrival delay

Weather delays influence delay severity but vary by airport

Airports exhibit distinct behavioral clusters based on delay characteristics

PCA confirms strong correlation among operational delay factors

▶ How to Run

Clone the repository

Install dependencies:

pip install -r requirements.txt


Download the dataset and place flights.csv in the root directory

Open and run Airline_Delay_Analysis.ipynb

👤 Author

Rachit Jaiswal
B.Tech – Computer Science Engineering
