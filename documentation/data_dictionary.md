# Data Dictionary

Fill this file with the exact columns from the dataset used by the Power BI report.

| Table            | Column         | Description                   | Data Type    |
|------------------|----------------|-------------------------------|--------------|
| All_Transactions | Date           | Transaction date              | Date         |
| All_Transactions | Transaction_ID | Unique transaction identifier | Text/Integer |
| All_Transactions | Amount         | Transaction amount            | Numeric      |
| All_Transactions | Reason         | Transaction reason/category   | Text         |
| All_Transactions | Service        | Service category              | Text         |

| Insurance        | Date           | Insurance transaction date    | Date         |
| Insurance        | Premium        | Insurance premium amount      | Numeric      |
| Insurance        | Payment_Status | Payment status                | Text         |
| Insurance        | Insurance_Type | Insurance category            | Text         |

| Loans            | Date           | Loan transaction date         | Date         |
| Loans            | Loan_Amount    | Loan amount                   | Numeric      |
| Loans            | Payment_Status | Payment status                | Text         |
| Loans            | Loan_Type      | Loan category                 | Text         |

| Money_Transfer   | Date           | Transfer date                 | Date         |
| Money_Transfer   | Amount         | Transfer amount               | Numeric      |
| Money_Transfer   | Payment_Status | Transfer status               | Text         |
| Money_Transfer   | Transfer_Type  | Transfer category             | Text         |

| Recharge_Bills   | Date           | Recharge/bill date            | Date         |
| Recharge_Bills   | Amount         | Payment amount                | Numeric      |
| Recharge_Bills   | Payment_Status | Payment status                | Text         |
| Recharge_Bills   | Recharge_Type  | Recharge/bill category        | Text         |
