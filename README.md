# OIBSIP_DataAnalytics_Task2

# Customer Segmentation Analysis using K-Means Clustering

## Project Overview

Customer segmentation is a crucial marketing strategy that enables organizations to understand customer behavior and create personalized experiences.

This project focuses on analyzing customer demographics and purchasing behavior using machine learning techniques. The primary objective is to identify distinct customer groups based on income, spending patterns, and purchasing habits.

The project was completed as part of the **Data Analytics Internship Program at Oasis Infobyte**.

---

## Organization

**Oasis Infobyte**

Internship Domain:
Data Analytics

---

## Student Information

**Name:** Sayed Amir Hamza

**Institution:** Anjuman-I-Islam's Kalsekar Technical Campus (AIKTC)

**Program:** Bachelor of Engineering

**Department:** Computer Engineering

---

## Project Objectives

* Perform data cleaning and preprocessing
* Analyze customer purchasing behavior
* Calculate descriptive statistics
* Explore customer spending patterns
* Apply K-Means Clustering
* Identify customer segments
* Generate actionable business insights
* Recommend marketing strategies

---

## Dataset Information

Dataset Source:

Marketing Analytics Customer Segmentation Dataset

Total Records:

```text
2205 Customers
```

Total Features Used:

```text
10 Features
```

Selected Features:

```text
Income
Kidhome
Teenhome
Recency
MntWines
MntFruits
MntMeatProducts
MntFishProducts
MntSweetProducts
MntGoldProds
```

---

## Tools and Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Jupyter Notebook

---

## Data Cleaning

The dataset was inspected for:

* Missing Values
* Duplicate Records
* Data Consistency
* Data Types

### Findings

✅ No Missing Values

✅ Dataset Ready for Analysis

---

## Exploratory Data Analysis

### Income Distribution

Analysis of customer income levels revealed a wide range of purchasing power among customers.

### Customer Spending Distribution

Total customer spending was calculated by combining spending across multiple product categories.

### Income vs Spending

A strong positive relationship was observed between income and customer spending.

---

## Correlation Analysis

A correlation heatmap was created to identify relationships between features.

### Key Findings

* Income strongly correlates with Total Spending
* Wine purchases have the strongest relationship with total expenditure
* Meat product purchases also significantly influence customer spending
* Customers with children generally exhibit lower spending patterns

---

## Customer Segmentation

### K-Means Clustering

K-Means clustering was applied to segment customers into distinct groups.

### Optimal Number of Clusters

The Elbow Method indicated:

```text
K = 4
```

---

## Customer Segments

### Cluster 0 – Premium Customers

Average Income:

```text
₹79,154
```

Average Spending:

```text
₹1,645
```

Characteristics:

* Highest income group
* Highest spending group
* Most valuable customers

---

### Cluster 2 – High Value Customers

Average Income:

```text
₹66,460
```

Average Spending:

```text
₹937
```

Characteristics:

* Strong purchasing power
* Consistent spending behavior

---

### Cluster 3 – Average Customers

Average Income:

```text
₹48,593
```

Average Spending:

```text
₹276
```

Characteristics:

* Moderate spending behavior
* Growth opportunity segment

---

### Cluster 1 – Low Value Customers

Average Income:

```text
₹27,321
```

Average Spending:

```text
₹76
```

Characteristics:

* Lowest spending behavior
* Require engagement campaigns

---

## Visualizations

### Income Distribution

<img width="695" height="470" alt="Income Distribution" src="https://github.com/user-attachments/assets/24d62b4a-66b3-4d31-9bd3-6c25c1c22333" />


---

### Customer Spending Distribution

<img width="695" height="470" alt="Customer Spending Distribution" src="https://github.com/user-attachments/assets/a0a39519-c729-4ab4-bea7-dfeb3a0c893b" />


---

### Income vs Spending

<img width="704" height="470" alt="Income vs Spending" src="https://github.com/user-attachments/assets/020a94ee-47a6-4f19-9258-717f91f96e5c" />


---

### Correlation Heatmap

<img width="883" height="642" alt="Feature Correlation Heatmap" src="https://github.com/user-attachments/assets/da1dc154-d657-4065-a957-1758031a4f52" />


---

### Elbow Method

<img width="704" height="470" alt="Elbow method" src="https://github.com/user-attachments/assets/fab8fa7e-1b0b-4f90-b854-52de9e2aa73d" />


---

### Customer Segments

![Uploading Customer Segmentation.png…]()


---

## Business Insights

### Key Findings

1. Customer income strongly influences spending behavior.

2. Premium customers generate the highest revenue.

3. Wine and meat products contribute significantly to customer expenditure.

4. Low-value customers require retention and engagement strategies.

5. Customer segmentation enables targeted marketing and personalized campaigns.

---

## Recommendations

### Premium Customers

* VIP Loyalty Programs
* Exclusive Offers
* Premium Product Recommendations

### High Value Customers

* Upselling Campaigns
* Personalized Discounts

### Average Customers

* Product Bundles
* Seasonal Promotions

### Low Value Customers

* Discount Campaigns
* Re-engagement Programs

---

## Conclusion

Customer segmentation analysis successfully identified four distinct customer groups using K-Means clustering.

The results demonstrate how machine learning and data analytics can transform customer data into actionable business insights. These findings can support targeted marketing, improve customer retention, and enhance overall business performance.

