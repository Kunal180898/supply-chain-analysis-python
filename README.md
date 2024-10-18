# supply-chain-analysis-python
Python based project

Project Overview
This project focuses on analyzing supply chain data to extract valuable insights into customer behavior, profitability, and operational efficiency. By leveraging Python and visualization libraries such as Matplotlib, the project aims to identify patterns in customer orders, profitability per order, and the impact of discount rates on order quantities. The findings from this analysis can help optimize decision-making strategies to enhance customer satisfaction and improve profitability.

Dataset
The dataset contains the following key features:

Customer Information: customer_id, customer_city, customer_country, customer_segment, etc.
Order Details: order_id, order_date, order_item_quantity, order_item_discount_rate, order_item_profit_ratio, etc.
Sales and Profit Data: sales, order_profit_per_order, order_item_total_amount, etc.
Shipping Information: shipping_date, shipping_mode, etc.

Key Insights and Conclusions
1. Customer Loyalty and Repeat Orders
We analyzed the number of orders per customer to identify repeat buyers. Customers who place multiple orders can be targeted with loyalty programs and special offers to further increase customer retention and satisfaction.
Conclusion:
Customers who place repeated orders should be rewarded with special offers or loyalty rewards to enhance customer satisfaction and build long-term trust.

2. Profitability by Order Quantity
A correlation analysis between order item quantity and order profit per order was conducted to understand how order quantities impact profitability. Surprisingly, the analysis revealed that higher quantities do not necessarily lead to higher profits.
Conclusion:
Profitability is not significantly boosted by increasing the order quantity. In fact, the data shows that single-item orders tend to bring in more profits. To address this, optimization strategies, such as carefully planned discounts for bulk orders, are recommended to reduce losses and improve profit margins.

4. Discount Rate vs. Quantity Ordered
An analysis of the relationship between discount rates and the quantity ordered revealed that discounts are applied relatively uniformly across different order quantities, with noticeable clusters at fixed discount rate tiers (e.g., 10%, 15%, 20%).
Conclusion:
There is no significant correlation between discount rates and the quantity ordered. This suggests that discount rates are applied in a standardized manner across orders of various sizes. To optimize sales and profitability, the company should consider adjusting discount strategies, offering greater incentives for larger orders while being cautious about discounts for smaller quantities.

Visualizations
The project includes several visualizations that help convey these insights:
Order Profit vs. Quantity Ordered
Discount Rate vs. Quantity Ordered
Customer Order Frequency Analysis

