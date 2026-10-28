# Decode Internship Project 2: Exploratory Data Analysis (EDA) Using Excel

## Project Overview

This project involved performing Exploratory Data Analysis (EDA) on an e-commerce dataset using Microsoft Excel. The objective was to examine order patterns, product demand, recorded order values, payment methods, referral sources, coupon code usage, and order statuses to identify meaningful insights that could support business decision-making.

#

## Dataset Description

The dataset contains **1,200 order records and 14 columns**, covering the period from January 2023 to June 2025.

Key columns include:

* OrderID
* Date
* CustomerID
* Product
* Quantity
* UnitPrice
* PaymentMethod
* OrderStatus
* ItemsInCart
* Couponcode
* ReferralSource
* TotalPrice

#

## Tools Used

* Microsoft Excel
* PivotTables
* Excel formulas
* Descriptive statistics
* Interquartile Range (IQR) method for outlier detection

#

## Analysis Performed

### 1. Data Quality Assessment

* Checked for missing values.
* Checked for duplicate records.
* Examined descriptive statistics for numerical variables.
* Identified potential outliers in the TotalPrice column using the IQR method.

### 2. Descriptive Statistics

Calculated the count, mean, median, minimum, and maximum for Quantity, UnitPrice, ItemsInCart, and TotalPrice.

### 3. Product Analysis

Examined product distribution and total quantities to understand differences in recorded product demand.

### 4. Order Status Analysis

Analyzed the distribution of cancelled, delivered, pending, returned, and shipped orders.

### 5. Monthly Trend Analysis

Examined monthly TotalPrice patterns across the available years to identify periods with higher and lower recorded order values.

### 6. Payment Method Analysis

Compared order counts and total recorded order values across payment methods.

### 7. Referral Source Analysis

Examined order counts and quantities associated with different referral sources.

### 8. Coupon Code Analysis

Compared coupon code usage, total recorded order values, and order status distributions across coupon categories.

### 9. Outlier Analysis

Applied the IQR method to identify unusually high TotalPrice values and examined the corresponding records.

#

## Key Findings

* **Product demand:** Chair recorded the highest total quantity at 562 units, while Phone recorded the lowest at 411 units.
* **Order status:** Cancelled orders were the most frequent status, accounting for 250 orders (20.83%). Delivered orders accounted for 231 orders (19.25%).
* **Monthly trends:** June had the highest combined monthly recorded order value at 170,616.13, while September had the lowest at 69,321.65.
* **Yearly comparison:** Total recorded order value decreased by approximately 13.1% from 2023 to 2024. The 2025 dataset covers only January to June.
* **Payment methods:** Online was the most frequently recorded payment method, with 258 orders. Credit Card recorded the highest total order value at 263,847.63.
* **Referral sources:** Instagram had the highest order count at 259, while Referral had the lowest at 222.
* **Coupon codes:** Freeship appeared in the most orders, with 313, and recorded the highest total order value at 335,036.99.
* **Outliers:** Eight potential upper outliers were identified. All had a quantity of five units, the maximum in the dataset, and their TotalPrice values were consistent with the Quantity × UnitPrice calculation. They were retained for analysis.


## Conclusion

This project provided insights into product demand, order patterns, payment methods, referral sources, coupon usage, and changes in recorded order values.

The analysis also identified potential outliers and areas that may require further investigation. These findings demonstrate how Excel can be used to explore data, identify patterns, and support evidence-based business decisions.

**Important note:** TotalPrice summaries include all recorded order statuses, including cancelled and returned orders. Therefore, the figures represent recorded order values rather than confirmed revenue.

#

## Skills Demonstrated

* Data cleaning and quality checks
* Exploratory Data Analysis (EDA)
* Descriptive statistics
* Excel PivotTables
* Outlier detection
* Trend analysis
* Data interpretation
* Business insight generation
* Analytical thinking

#

Decode-Internship-Project-2-EDA/
│


├── README.md


├── Decode_EDA_Project.xlsx


└── Dataset.xlsx
