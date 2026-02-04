# Airline Delay Root-Cause Analysis

This project analyzes real-world airline operations data to identify key factors contributing to flight delays.  
Instead of focusing only on prediction, the project emphasizes understanding delay causes and airport-level behavior patterns using machine learning and data analysis techniques.

---

## Objectives
- Analyze operational, weather, and system-related contributors to flight delays  
- Predict arrival delay magnitude and identify high-risk delayed flights  
- Discover airport-level delay patterns using unsupervised learning  

---

## Dataset
- Source: U.S. Department of Transportation (via Kaggle)
- Records: Commercial airline flights
- Key Features:
  - Arrival Delay
  - Airline Delay
  - Weather Delay
  - Air System Delay
  - Late Aircraft Delay
  - Month, Day of Week, Origin Airport

---

## Methodology
- Data Cleaning and Preprocessing using Pandas
- Exploratory Data Analysis (EDA) for trend identification
- Regression modeling to estimate arrival delay duration
- Classification modeling to identify delayed vs non-delayed flights
- K-Means clustering to group airports by delay behavior
- Principal Component Analysis (PCA) to reduce correlated delay features

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Key Insights
- Operational delays contribute more to delay frequency, while weather delays impact severity  
- Airports exhibit distinct delay behavior patterns that can be grouped using clustering  
- PCA reveals that a small number of components explain most operational delay variance  

---

## How to Run
1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Open and run the notebook in the `notebooks/` folder  

---

## Author
Rachit Jaiswal
