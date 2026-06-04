# Decodelab-Project3
This project focuses on analyzing an ecommerce retail dataset using SQL to extract meaningful business insights. The analysis explores key performance metrics such as revenue, product performance, payment methods, referral sources, coupon usage, and order status distribution.


# Ecommerce Sales Insights Using SQL (Project 3)

## Dataset
[Ecommerce_sales_data.csv](https://github.com/user-attachments/files/28593053/Ecommerce_sales_data.csv)

The dataset includes ecommerce transaction data such as:
- Order ID
- Product
- Quantity
- Unit Price
- Total Price
- Order Status
- Payment Method
- Referral Source
- Coupon Code


## Key Business Insights

### Product Performance

- Top revenue-generating products include **Chair (195,620.11)** and **Printer (195,612.61)**.
- The lowest revenue product is **Phone (151,722.39)**.
- Product demand is highest for **Printer (181 orders)** and lowest for **Phone (156 orders)**.
- Revenue per order varies significantly across products, showing pricing and demand imbalance.


### Revenue by Product (Full Ranking)

- Chair – 195,620.11  
- Printer – 195,612.61  
- Laptop – 192,126.56  
- Tablet – 186,568.95  
- Monitor – 175,651.41  
- Desk – 167,459.93  
- Phone – 151,722.39  


### Payment Method Analysis

- Credit Card – 263,847.63  
- Online – 262,442.94  
- Cash – 259,786.29  
- Gift Card – 246,323.92  
- Debit Card – 232,361.18  

Credit Card and Online payments dominate revenue contribution.

---
### Referral Source Performance

**Revenue Contribution:**
- Instagram – 275,285.45  
- Email – 261,808.55  
- Google – 250,441.48  
- Facebook – 250,410.90  
- Referral – 226,815.58  

**Order Volume:**
- Instagram – 259  
- Email – 250  
- Google – 241  
- Facebook – 228  
- Referral – 222  

Instagram is the strongest acquisition channel in both revenue and order volume.

---
### Coupon Code Analysis

- FREESHIP – 313 orders  
- No Coupon – 309 orders  
- WINTER15 – 292 orders  
- SAVE10 – 286 orders  

Most customers place orders without coupon usage, indicating strong organic purchasing behavior.


### No Coupon Revenue

- Total revenue from non-coupon orders: **322,401.41**

A large portion of revenue is generated without discounts, improving profitability.

---
### Order Status Performance

- Cancelled – 276,396.21  
- Pending – 256,328.15  
- Shipped – 246,159.58  
- Returned – 243,277.70  
- Delivered – 242,600.32  

Cancelled and Pending orders generate unexpectedly high revenue share, indicating possible operational inefficiencies.


### Order Status Insight

- Total Delivered Orders: **321**

Delivered orders represent successful fulfillment but are not the highest revenue contributor.

### Revenue by Product (Range Analysis)

- Highest single order values vary between **~3,190 to 3,456**
- Lowest order values range between **~11 to 30**

This shows inconsistent order sizes across products and potential pricing variation.

---
## Key Findings

- Instagram is the strongest referral channel in both revenue and order volume.
- Credit Card is the most preferred payment method.
- Chair and Printer are the highest revenue-generating products.
- Most customers do not use coupons, contributing to higher profitability.
- Significant revenue is still associated with cancelled and pending orders.


## Conclusion
This project demonstrates the use of SQL to analyze an ecommerce dataset and extract meaningful business insights.

The following skills were applied throughout the project:
- Filtering data using WHERE to focus on specific conditions  
- Performing calculations using SUM, AVG, and COUNT  
- Grouping data using GROUP BY to summarize information  
- Organizing results using ORDER BY for better interpretation  

Overall, the analysis helped identify key trends in revenue, product performance, customer behavior, and sales channels.

## Tools Used
- SQL (MySQL / SQL Server)

---
## Author 
**Chidera Ochiaka**

---
