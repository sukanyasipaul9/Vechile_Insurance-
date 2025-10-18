🚗 Vehicle Insurance EDA Project
📌 Objective



To perform Exploratory Data Analysis (EDA) on a large vehicle insurance dataset to uncover insights about customer demographics, vehicle information, and claim response patterns.

📊 Dataset Overview
Rows: 381,109
Columns: 12
Target Variable: Response (1 = interested in insurance, 0 = not interested)
Key Features: Gender, Age, Driving_License, Vehicle_Age, Vehicle_Damage, Annual_Premium, Policy_Sales_Channel, Region_Code, Vintage
🧹 Data Cleaning
Checked for null values (none found)
Outlier detection using IQR method
Label Encoding for categorical columns
Filled missing or inconsistent values using mean imputation
📈 Analysis Performed
Univariate Analysis: Age, Gender, and Premium distributions
Bivariate Analysis: Age vs Response, Vehicle Damage vs Response
Region-wise Trends: Claim frequencies across regional codes
Customer Type: Previously insured vs new customers
Premium Analysis: Annual Premium vs Response correlation
🔍 Insights
Customers with vehicle damage are more likely to claim insurance.
Age group 30–50 shows the highest engagement.
Certain sales channels lead to higher response rates.
Previously insured customers tend to have lower claim interest.
🛠️ Tools Used



Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn[Mini_Project2_Vechicle_insurance_1760260144.pdf](https://github.com/user-attachments/files/22985848/Mini_Project2_Vechicle_insurance_1760260144.pdf)
