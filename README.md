# Amazon Sales Data Analysis 📊

This project focuses on analyzing Amazon sales data using Python to extract meaningful insights through data cleaning, exploratory data analysis (EDA), and multivariate analysis.

## 🔧 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📂 Dataset
The dataset contains information such as:
- Order number
- Price
- Rankings
- Number of reviews
- Ratings
- Genre
- Year of publication

## 🧹 Data Preprocessing
- Handled missing values using mean and categorical imputation
- Removed or capped outliers using the IQR method
- Corrected data types for analysis

## 📊 Analysis Performed
- Univariate analysis (distribution of price, ratings, genres)
- Bivariate analysis 
- Multivariate analysis using correlation matrix, scatter plots, and pivot tables
- Outlier handling using `clip()` and IQR method

## 📈 Key Insights
- Ratings are more influenced by number of reviews than price
- Certain genres consistently show higher average ratings
- Extreme price values were controlled to improve analysis accuracy


