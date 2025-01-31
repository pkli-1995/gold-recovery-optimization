# Gold Recovery Optimization 🏆🔬  
A machine learning project to predict gold recovery rates in industrial flotation processes.

## 📌 Project Overview  
Gold recovery in mineral processing is crucial for profitability. This project applies **machine learning techniques** to optimize recovery rates by analyzing industrial flotation process data.

## 🛠 Technologies Used  
- **Python** (Pandas, NumPy, Scikit-Learn, XGBoost)
- **Jupyter Notebook**
- **Matplotlib, Seaborn** (for data visualization)
- **GitHub**

## 📊 Dataset  
- Industrial data on gold ore recovery from the **flotation process**.
- Features include **feed composition, process parameters, and final recovery percentages**.

📂 Dataset Access
Due to GitHub's file size limitations, the dataset required for this project is hosted on Google Drive.
📌 Download the dataset here → [Gold Recovery Dataset](https://drive.google.com/uc?id=1bCh0mS6FrD5dyE1E7fQ5s8Cd0lT3QyR-)

How to Use the Dataset in Jupyter Notebook
To ensure your Jupyter Notebook runs correctly, update the code snippet below to automatically download the dataset:

import pandas as pd

# Google Drive link
url = "https://drive.google.com/uc?id=1bCh0mS6FrD5dyE1E7fQ5s8Cd0lT3QyR-"

# Load the dataset
df = pd.read_csv(url)

# Display the first few rows
df.head()

## 🔍 Key Insights
- Applied feature engineering to remove inconsistencies and optimize performance.
- Trained Random Forest and XGBoost models, achieving high prediction accuracy.
- Used Mean Absolute Error (MAE) as an evaluation metric, achieving a near-zero error rate.

## ▶ How to Run

1. Clone this repository:
git clone https://github.com/yourusername/gold-recovery-optimization.git
2.Open gold_recovery_optimization.ipynb in Jupyter Notebook.
3.Run all cells to process the data and generate model predictions.

If you encounter any issues accessing the dataset, ensure:
- The sharing settings allow anyone with the link to view the file.
- You replace "YOUR_GOOGLE_DRIVE_LINK" with the actual download link if necessary.
