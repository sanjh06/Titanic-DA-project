# Titanic-DA-project
A foundational  Data Analytics project using the Titanic dataset covering data cleaning, visualization, outlier handling, feature engineering and Model training.
Project Overview
📁 Dataset: Titanic dataset (train.csv & test.csv)

🧹 Data Cleaning: Removed or filled missing values, dropped unnecessary columns

📊 Data Visualization: Used plots to understand patterns and correlations

🤖 Model Training: Basic machine learning model (KNN) to predict survival

🧼 Data Cleaning
Handled missing values in:
searching for null values and duplicates
sorting the values in a column for a more understanding

📊 Data Visualization
Used matplotlib and seaborn to explore:

Survival counts

Survival by gender and passenger class

Age distribution

Heatmap to view correlations and missing data

🤖 Model Training
Used a K-Nearest Neighbors (KNN) classifier for prediction

Accuracy Score: ~71%

 Model training was done after essential preprocessing .

📁 Project Structure
titanic-project/
├── data/
│   ├── train.csv
│   └── test.csv
├── titanic_analysis.ipynb
├── README.md
└── visuals/
    ├── survival_by_gender.png
    └── heatmap.png
🧰 Libraries Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🚀 Future Improvements
Perform feature engineering (e.g., FamilySize, IsAlone, age binning)
Encode categorical variables using One-Hot or Label Encoding
