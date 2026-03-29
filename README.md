# Diwali_Sales_Analysis

🎆** Diwali Sales Data Analysis (Python EDA Project)**
📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on Diwali sales data using Python to uncover customer purchasing behavior, sales trends, and business insights.
The goal is to help businesses understand target customers, high-performing regions, and product categories to improve marketing strategies during festive seasons.
________________________________________
🎯 **Objectives**
•	Analyze customer demographics (Gender, Age, Marital Status)
•	Identify top-performing states and occupations
•	Understand product category demand
•	Extract actionable insights for business growth
________________________________________
🛠️ **Tech Stack**
•	Python
•	NumPy
•	Pandas
•	Matplotlib
•	Seaborn
________________________________________
📂 **Dataset**
•	Dataset: Diwali Sales Data.csv
•	Contains information such as:
o	User demographics
o	Product categories
o	Orders and sales amount
o	Location (State)
________________________________________
🔧 **Data Cleaning & Preprocessing**
•	Removed unnecessary columns (Status, unnamed1)
•	Handled missing values using dropna()
•	Converted Amount column to integer type
•	Renamed columns for better readability
________________________________________
📊 **Exploratory Data Analysis**
👩‍🦰 Gender Analysis
•	Majority of buyers are female
•	Females have higher purchasing power than males
________________________________________
🎂 **Age Group Analysis**
•	Highest buyers belong to 26–35 age group
•	Female customers dominate this segment
________________________________________
📍 **State-wise Analysis**
•	Top states by sales and orders:
o	Uttar Pradesh
o	Maharashtra
o	Karnataka
________________________________________
💍** Marital Status**
•	Married women are the primary buyers
•	They contribute significantly to total sales
________________________________________
💼 **Occupation Analysis**
Top contributing sectors:
•	IT
•	Healthcare
•	Aviation
________________________________________
🛍️ **Product Category Analysis**
Top-selling categories:
•	Food
•	Clothing
•	Electronics
________________________________________
🏆 **Top Products**
•	Identified top 10 most sold products using order count
________________________________________
📈** Key Insights**
✔ Female customers are the dominant buyers
✔ Age group 26–35 is the most active segment
✔ Married women have higher purchasing power
✔ Top states driving revenue: UP, Maharashtra, Karnataka
✔ High demand sectors: IT, Healthcare, Aviation
✔ Best-performing categories: Food, Clothing, Electronics
________________________________________
🚀** Conclusion**
Target Customer Profile:
Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are more likely to purchase products, especially in Food, Clothing, and Electronics categories.
________________________________________
📌 **Future Improvements**
•	Add predictive analysis (sales forecasting)
•	Build interactive dashboards using Power BI/Tableau
•	Perform customer segmentation using clustering
________________________________________
💻 **Sample Code**
# Group by Gender and calculate total sales
sales_gen = df.groupby(['Gender'], as_index=False)['Amount'].sum()

sns.barplot(x='Gender', y='Amount', data=sales_gen)
________________________________________
⭐ **How to Run the Project**
1.	Clone the repository
git clone https://github.com/your-usernamesunilkumar_analyst/Diwali_Sales_Analysis.git
pip install pandas numpy matplotlib seaborn
3.	Run the Jupyter Notebook
________________________________________
🙌 **Acknowledgment**
This project is created for learning and practicing data analysis using Python.
________________________________________
📬 **Contact**
If you liked this project, feel free to connect!

