# PROJECT-CUSTOMER-LIFE-TIME-VALUE-PREDICTION-MODEL
In the below showing a customer csv file used to Predict the lifetime value (LTV) of customers based on their purchase behavior to aid in targeted marketing
[customer_data.csv](https://github.com/user-attachments/files/20122174/customer_data.csv)
In the below image code i used the above csv file contained customer data for Preprocess customer purchase history (merge transactions with customer IDs)
![Screenshot 2025-05-09 180456](https://github.com/user-attachments/assets/f9aea118-a8dd-4102-bb79-3d387c8d46b7)
In the above code - The code reads customer data from the CSV and iterates over every record, extracting the customer ID (name) along with transactions details. These are then assembled into a new, consolidated DataFrame (trans_df) that merges customer IDs with their individual purchase transactions.
In the below image code is used for the Feature engineering: Frequency, Recency, AOV (Avg Order Value)
![Screenshot 2025-05-09 180956](https://github.com/user-attachments/assets/3ceef17a-ceb5-4c63-84bf-c097eedb8fab)
In the above code - The code groups the transactions by customer name and computes key metrics: it calculates recency (days since the last transaction) by subtracting the latest transaction date from the snapshot date, frequency as the count of transactions, and AOV as the mean transaction amount. These features are essential for profiling customer behavior
