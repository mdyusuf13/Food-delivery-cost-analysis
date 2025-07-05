# Food Delivery Metrics Analysis and Visualization
Download project report: [Food delivery analysis project report(pdf)](https://drive.google.com/file/d/1mdwWDPtIYGeTXTVqlNFbRNaL3u0IZN0R/view?usp=drive_link)
Project Title:
Food Delivery Metrics Analysis and Visualization

Prepared by:
Mohammed Yusuf A

Date:
August 2024

1. Introduction:
This project analyzes food delivery transaction data to derive actionable insights about revenue, costs, and operational performance. The objective was to clean, process, and visualize key metrics to understand business trends and profitability in online food delivery.

2. Dataset Overview:
Source: Swiggy sample dataset used in WScube Masterclass

Records: 1,000 orders

Columns Included:

Order Value, Delivery Fee, Commission Fee, Payment Processing Fee, Refunds/Chargebacks, Discounts and Offers, Payment Method, Restaurant ID, Order Date and Time, Delivery Date and Time

This dataset represents transactions processed by a food delivery platform.

3. Tools and Technologies:
Development Environment: Google Colab

Programming Language: Python

Libraries Used:

Pandas (data manipulation)

NumPy (numerical operations)

Matplotlib (visualization)

Seaborn (visualization)

4. Data Cleaning and Preprocessing:
Key cleaning steps performed:

Converted date columns (Order Date and Time, Delivery Date and Time) from object to datetime format.

Calculated additional fields:

Total Revenue = Order Value + Delivery Fee

Total Cost = Commission Fee + Payment Processing Fee + Refunds/Chargebacks

Total Profit = Total Revenue - Total Cost

Verified dataset integrity using .info() and .head() functions.

This ensured the data was ready for accurate analysis.

5. Exploratory Data Analysis:
Initial exploration was performed to understand:

Payment methods distribution

Discounts applied

Order values per restaurant

Delivery times

Data profiling revealed common discount types and highlighted Cash on Delivery as the dominant payment method.

6. Metrics Calculation:
The following metrics were calculated:

Total Revenue: ₹1,082,589

Total Cost: ₹185,122

Total Profit: ₹897,467

Most Popular Payment Method: Cash on Delivery

Order Volume by Discount:

10% Discount – 233 orders

15% New User – 198 orders

5% on App – 183 orders

₹50 Off Promo – 201 orders

Top 3 Restaurants by Order Value:

R2726 – ₹6,794

R2083 – ₹6,291

R2933 – ₹6,049

Average Delivery Time: Approx. 1 hour

7. Data Visualization:
Visualizations created to illustrate findings:

Financial Overview (Bar Chart), Showed total revenue, cost, and profit, Payment Method Distribution (Pie Chart), Highlighted Cash on Delivery share, Order Volume by Discounts (Bar Chart), Compared discount types, Delivery Time Distribution (Histogram).

Analyzed delivery time frequencies:

Top Performing Restaurants (Bar Chart)

Ranked restaurants by sales

8. Insights and Interpretation:
The platform generated substantial profit margins (approx. ₹900,000 over 1,000 orders).

Cash on Delivery accounted for the majority of payments, indicating potential risk in payment collection.

Discounts were widely used, especially the 10% and ₹50 Off promotions.

Delivery times averaged around 1 hour, suggesting moderate operational efficiency.

A small number of restaurants contributed disproportionately to revenue.

These insights can help optimize marketing spend, payment options, and restaurant partnerships.

9. Conclusion:
This project demonstrated how Python-based analysis can reveal critical business insights from raw delivery data. Cleaning, processing, and visualizing 1,000 food delivery transactions provided a clear view of profitability drivers, operational patterns, and customer behaviors.

10. References:
WScube Masterclass: Food Delivery Cost Analysis

Python official documentation

Pandas, Matplotlib, and Seaborn guides

Contact
For questions or further information, please contact mdy717174@gmail.com


