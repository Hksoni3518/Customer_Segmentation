# Customer Segmentation Using Machine Learning

## 📌 Project Overview

Customer segmentation is the process of dividing customers into meaningful groups based on their demographic characteristics, purchasing behavior, satisfaction, and engagement.

This project uses **K-Means Clustering** to segment **350 customers into four distinct customer groups**. The analysis considers customer demographics, spending patterns, purchase activity, customer ratings, satisfaction, membership type, and purchase recency.

The project was developed using **Python in Google Colab**, and an interactive dashboard was created using **Plotly** to visualize customer segments and understand their characteristics.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Segment customers based on demographic and behavioral characteristics.
- Identify meaningful customer groups using **K-Means Clustering**.
- Analyze customer spending and purchasing patterns.
- Understand customer satisfaction and engagement.
- Identify high-value and low-value customer segments.
- Visualize customer segments using Python.
- Generate actionable business insights.
- Recommend targeted strategies for different customer segments.

---

# 📊 Dataset

The dataset contains information about **350 customers** and includes demographic, purchasing, and behavioral attributes.

## Dataset Features

| Column | Description |
|---|---|
| `Customer_ID` | Unique identifier of each customer |
| `Gender` | Customer gender |
| `Age` | Customer age |
| `City` | Customer's city |
| `Membership_Type` | Customer membership category |
| `Total_Spend` | Total amount spent by the customer |
| `Items_Purchased` | Number of items purchased |
| `Average_Rating` | Average rating given by the customer |
| `Discount_Applied` | Whether a discount was applied |
| `Days_Since_Last_Purchase` | Number of days since the customer's last purchase |
| `Satisfaction_Level` | Customer satisfaction level |
| `Cluster` | Customer cluster generated using K-Means |

### Dataset Preparation

The dataset was prepared using Python and included:

- Missing-value handling
- Duplicate checking
- Data type validation
- Exploratory Data Analysis
- One-Hot Encoding of categorical variables
- Feature scaling using `StandardScaler`

`Customer_ID` was not used as a clustering feature because it is an identifier rather than a behavioral attribute.

---

# 🔄 Project Workflow

The complete project workflow is:

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Selection
     ↓
Categorical Encoding
     ↓
Feature Scaling
     ↓
Elbow Method
     ↓
K-Means Clustering
     ↓
Cluster Analysis
     ↓
Customer Segment Identification
     ↓
Interactive Python Dashboard
     ↓
Key Business Insights
     ↓
Business Recommendations
