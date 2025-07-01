# Data-Preprocessing
Data Preprocessing Project

This project demonstrates data preprocessing techniques on a small dataset containing information about customers from different countries.

📁 Dataset Columns:

Country

Age

Salary

Purchased (Yes/No)


🔧 What is Data Preprocessing?

Data preprocessing is the process of cleaning and preparing raw data to make it suitable for analysis or machine learning. It includes handling missing values, encoding categorical data, and scaling numerical values.

✅ Key Steps Performed:

Handling missing values (in Age and Salary)

Encoding categorical data (Country and Purchased)

Feature scaling (standardizing Age and Salary)

# Ordinal Encoding

# Sample data
data={
    'CustomerID':['C001','C002','C003','C004','C005','C006','C007','C008'],
    'Education_Level':['High School','Bachelors','Masters','PHD','Bachelors','High School','PHD','Masters'],
    'Product_Quality':['Low','Medium','High','Medium','Low','High','Medium','High'],
    'Satisfacation_Level':['Poor','Average','Excellent','Good','Average','Poor','Average','Excellent']
}
df=pd.DataFrame(data)
📁 Dataset Columns:

CustomerID

Education_Level (High School, Bachelors, Masters, PHD)

Product_Quality (Low, Medium, High)

Satisfaction_Level (Poor, Average, Good, Excellent)


🔧 What is Ordinal Encoding?

Ordinal Encoding is used to convert ordered categories into numbers based on their rank.
Example:

Poor → 0, Average → 1, Good → 2, Excellent → 3


🛠 Tools Used:

Python

Pandas

Scikit-learn

🛠 Tools Used:

Python (Pandas, NumPy, Scikit-learn)

Jupyter Notebook
