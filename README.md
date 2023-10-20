# Retail_Store_Customer_Segmentation
A Popular Global Retail Chain dataset which is available on Kaggle [Dataset specifications](https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset)
has been used to analyse customer segmentation on the basis of customer transactions and behavior aspects. 
As this dataset is so popular that all the tables from different sources are merged into one dataset. It comprises of 4 tables: (a) Orders Table, (b) Customers Table, (C) Products Table, (d) Sales Table.

When conducting customer segmentation using K-means or PCA clustering technique ![Segmentation](C:\Users\panka\OneDrive\Desktop\Class Folder\Github\Retail_Store_Customer_Segmentation\Image)
, it's important to choose the right features (columns) that reflect customer behavior and characteristics. Here are the column considerations for feature selection and data preprocessing from that big dataset which reflects the customer segmentation based on there transactions and behavior:
Feature Selection:
Customer-related features: Focus on features that describe customer behavior and attributes. Relevant columns include 'customer_id'.
Sales-related features: Columns like 'sales,' 'quantity,' 'discount,' 'profit,' 'shipping_cost,' and 'order_priority' can provide insights into customer purchase behavior, profitability, and preferences.
Object Data Types: These are typically used for categorical variables, such as 'customer_id' and 'order_priority.' Categorical variables are common for customer segmentation because they help create distinct groups based on different categories or labels. Ensure that these categorical variables are appropriately encoded for analysis, such as using one-hot encoding.
Float64 Data Types: 'sales,' 'discount,' 'profit,' and 'shipping_cost' are floating-point variables. These are commonly used in segmentation analysis for financial and transactional data. They can help differentiate customers based on their purchasing behavior and profitability.







