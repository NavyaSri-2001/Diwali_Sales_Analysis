# Diwali_Sales_Analysis

# About Data:
1. The dataset represents data about sales that happened during diwali season.
2. The dataset consists of 11251 rows and 15 columns.
3. The data contains different columns like gender, age group, marital status, state, amount, occupation of buyer, product category, no.of orders etc.

# Data Cleaning and Data Manipulation:
Performed data cleaning and data manipulation on the given data as follows:
1. Using info() method found out no.of useless columns which are blank and removed them using drop function.
2. Using dropna() function removed the rows which had some null values.
3. Using astype() function changed the data type of Amount column from float to integer.
4. Using rename() function renamed some columns to more meaningful names.

# Exploratory Data Analysis:
1. Using countplot, barplot and groupby functions and using gender as a variable, found out that most of the buyers are females and even the purchasing power of females is greater than men.
2. Plotting graphs using age as a parameter and gender as hue found that most of the buyers are of age group between 26-35 yrs and majority are female.
3. Using state and no.of orders as parameters found that most of the orders & total sales/amount are from Uttar Pradesh, Maharashtra and Karnataka respectively.
4. Using marital status as a parameter found that most of the buyers are married (women) and they have high purchasing power.
5. Using occupation as a parameter found that most of the buyers are working in IT, Healthcare and Aviation sector.
6. Using product category as a parameter found that most of the sold products are from Food, Clothing and Electronics category.

# Conclusion:
Based on all the graphs we can infer that Married women of age group 26-35 yrs from UP, Maharastra and Karnataka working in IT, Healthcare and Aviation are more likely to buy products from Food, Clothing and Electronics category.

