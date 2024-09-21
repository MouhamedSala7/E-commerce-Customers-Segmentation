# 📌 Project Title: E-commerce Customers Segmentation

## 📊 Dashboard Overview

Below is a snapshot of the dashboard developed for visualizing customer demographics, coupon transactions, top-performing cities/branches, and customer retention trends:

(.![E-commerce](https://github.com/user-attachments/assets/dba4dbdb-2aea-4893-a165-15409e0700b7)


## 📌 Dataset Overview
The dataset consists of five interrelated tables, containing crucial information about customers, transactions, branches, and merchants. These tables are described below:

### 1. Customers Table
- `customer_id`: Unique identifier for each customer.
- `join_date`: The date the customer joined.

- `city_id`: The ID representing the customer's city.
- `gender_id`: The ID representing the customer's gender.

### 2. Genders Table
- `gender_id`: Unique identifier for each gender.
- `gender_name`: Name of the gender (e.g., male, female).

### 3. Cities Table
- `city_id`: Unique identifier for each city.
- `city_name`: Name of the city.

### 4. Transactions Table
- `transaction_id`: Unique identifier for each coupon transaction.
- `customer_id`: ID of the customer who performed the transaction.
- `transaction_date`: The date the coupon was claimed.
- `transaction_status`: Status of the coupon (e.g., claimed, burnt).
- `coupon_name`: The name of the coupon.
- `burn_date`: The date the coupon was burnt.
- `branch_id`: ID of the branch where the coupon was burnt.

### 5. Branches Table
- `branch_id`: Unique identifier for each branch.
- `merchant_id`: ID of the merchant who owns the branch.

### 6. Merchants Table
- `merchant_id`: Unique identifier for each merchant.
- `merchant_name`: Name of the merchant.

## 📌 Project Requirements

### 1. Build a Dashboard for Stakeholders
The goal is to design and develop a well-structured and informative dashboard that presents key insights from the dataset. The dashboard is aimed at helping stakeholders, such as business managers and marketing teams, make data-driven decisions.

### Key Visualizations:
- **Customer Demographics**: Breakdown of customers by gender and city.
- **Coupon Usage**: Insights into coupon transaction status (claimed vs. burnt) over time.
- **Top-performing Cities/Branches**: Highlighting the cities or branches with the highest number of successful coupon burns.
- **Customer Retention and Loyalty**: Patterns in customer coupon usage frequency and trends over time.

### Recommended Visualizations:
- **Pie charts**: For customer gender and city distributions.
- **Time-series line charts**: For coupon transactions over time.
- **Heatmaps or bar charts**: For city-wise or branch-wise coupon burn rates.
- **Histograms**: For customer retention and burn frequency patterns.

## 📌 Clustering & Customer Segmentation

### Unsupervised Machine Learning for Customer Segmentation
In addition to dashboard creation, the project also involves building an unsupervised machine learning model to segment customers based on their transactional behavior. The goal is to identify groups with similar behaviors to improve coupon strategies and retention efforts.

#### Steps:
1. **Feature Selection**:
   - Use demographic features like gender and city, and transactional features like coupon usage frequency and transaction status.
   
2. **Model Development**:
   - Implement and evaluate models such as K-Means, DBSCAN, or hierarchical clustering for customer segmentation.
   
3. **Model Evaluation**:
   - Evaluate using metrics such as Silhouette Score and Inertia for K-Means.
   ![Screenshot 2024-09-21 154830](https://github.com/user-attachments/assets/1eda83ee-64cd-417d-8430-1d5e42491066)

4. **Segment Analysis**:
   - Analyze customer groups based on transaction patterns and behavior.
![Screenshot 2024-09-21 155045](https://github.com/user-attachments/assets/204a666a-0848-4966-9a62-0142c9579d2e)



