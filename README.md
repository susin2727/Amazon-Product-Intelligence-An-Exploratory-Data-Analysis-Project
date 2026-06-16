# Exploratory Data Analysis of Amazon Products and Customer Reviews

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an Amazon Products dataset to uncover patterns, trends, and relationships between product pricing, discounts, ratings, and customer engagement.

The objective is to gain business insights using statistical analysis and data visualization techniques.

---

## Dataset Information

The dataset contains information about Amazon products, including:

* Product Name
* Product Category
* Actual Price
* Discounted Price
* Discount Percentage
* Product Rating
* Rating Count
* Product Description
* Customer Reviews

### Dataset Size

* Rows: 1465
* Columns: 16

---

## Objectives

* Understand the structure of the dataset
* Perform data cleaning and preprocessing
* Analyze product pricing and discounts
* Explore customer ratings and review patterns
* Identify relationships between key variables
* Generate actionable business insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning

The following preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Converted price columns to numeric format
* Converted discount percentages to numeric values
* Converted rating counts to numeric values
* Handled missing values in rating_count

---

## Exploratory Data Analysis

### Statistical Analysis

Performed descriptive statistics on:

* Actual Price
* Discounted Price
* Discount Percentage
* Rating Count

### Visualizations

* Rating Distribution Histogram
* Discount Distribution Histogram
* Correlation Heatmap
* Category Analysis
* Price Distribution Boxplot
* Discount vs Rating Scatter Plot
* Top Reviewed Products Analysis

---

## Key Findings

### Product Ratings

* Most products have ratings between 4.0 and 4.5.
* Low-rated products are relatively rare.
<img width="695" height="470" alt="rating_distribution" src="https://github.com/user-attachments/assets/a8ebabb2-4d2d-40a5-86a0-1e66a9a7dce0" />


### Discounts

* Average discount percentage is approximately 48%.
* Sellers frequently use discounts as a pricing strategy.
<img width="695" height="470" alt="Discount Percentage Distribution" src="https://github.com/user-attachments/assets/c2231558-fd5e-4a8c-a831-80caf3d584ef" />

### Pricing

* Products range from ₹39 to ₹139,900.
* Most products are priced below ₹1000.

### Categories

* USB Cables represent the largest product category in the dataset.

### Correlation Analysis

* Actual Price and Discounted Price have a strong positive correlation (0.96).
* Product ratings have very weak relationships with price and discount percentage.
* Higher discounts do not necessarily lead to better ratings.

---

## Business Insights

* Customer satisfaction is generally high across products.
* Product quality appears to influence ratings more than discounts.
* The dataset is dominated by electronics and computer accessories.
* Premium-priced products coexist with budget-friendly products, indicating a diverse marketplace.

---

## Conclusion

This analysis demonstrates how exploratory data analysis can be used to understand customer behavior, pricing strategies, and product performance on Amazon. The findings show that discounts alone do not guarantee higher ratings, while product quality and customer experience appear to play a larger role in customer satisfaction.

---

## Project Structure

```text
Amazon-EDA/
│
├── amazon.csv
├── Amazon_EDA.ipynb
├── README.md
├── images/
│   ├── rating_distribution.png
│   ├── correlation_heatmap.png
│   ├── correlation_heatmap.png
│   └── price_boxplot.png
```

---

## Author

Susinthiran A

Final Year Information Technology Student
