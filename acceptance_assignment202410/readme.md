# Assignment: Real-time Retail Transaction Simulation
## Objective:
To simulate real-time retail transactions and store them in a file for further analysis.
## Requirements:
1. **Transaction Generation**:
    - Create a Python script that generates random retail transactions every minute.
    - Each transaction should include the following fields:
        * transaction_id: A unique identifier.
        * timestamp: The current timestamp.
        * product_id: A random product ID.
        * quantity: A random integer between 1 and 5.
        * price: A random float between 5 and 100.
        * customer_id: A random customer ID.
2. **File Storage**:
    - Append generated transactions to a CSV file named retail_transactions.csv.
    - Ensure the CSV file has a header row with the field names.