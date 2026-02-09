💳 Customer Shopping Behavior Analysis
This project investigates consumer spending patterns and subscription dynamics across 3,900 unique transactions. By leveraging Python for data imputation, PostgreSQL for behavioral segmentation, and Power BI for demographic profiling, the study identifies high-value segments and provides data-driven strategies for loyalty optimization.

📊 Project Vital Signs
Total Revenue: $233,081.00.

Customer Base: 3,900 records.

Average Purchase: $59.76.

Top Revenue Segment: Young Adults ($62,143).

Subscription Rate: 27% (1,053 members).

🛠️ Technical Workflow
1. Python Exploratory Data Analysis (EDA)
Focused on preparing messy transactional data for reliable modeling:

Advanced Imputation: Addressed 37 missing values in 'Review Rating' by applying the median rating per product category to maintain data integrity.

Feature Engineering: Created the age_group dimension (Young Adult, Middle-aged, Adult, Senior) and calculated purchase_frequency_days.

Standardization: Converted all 18 columns to snake_case for seamless database migration.

2. SQL Behavioral Analysis
Executed deep-dive queries to identify profitability drivers:

Revenue by Demographics: Determined that while Clothing is the top category ($104,264), Footwear maintains the highest average review rating.

Subscription Impact: Analyzed churn risk by comparing repeat purchase frequency between subscribers and non-subscribers.

Regional Ranking: Identified Montana and California as high-density markets for targeted logistics.

3. Power BI Interactive Dashboard
Developed a multi-page report to visualize the consumer journey:

Segment Profiling: Integrated gender and age filters to observe real-time shifts in category preference.

Behavioral Heatmap: Visualized the correlation between shipping types (e.g., Next Day Air) and high-value orders.

💡 Strategic Business Recommendations
Subscription Push: Promote exclusive "Subscriber-Only" benefits to the 73% non-member base to increase predictable recurring revenue.

Age-Targeted Marketing: Direct "Clothing" and "Accessories" campaigns toward the Young Adult segment, as they currently represent the highest spending power.

Shipping Optimization: Evaluate the ROI of Free Shipping vs. Next Day Air, as shipping speed is a primary driver for the $59.76 average purchase amount.

Inventory Balancing: Leverage the success of high-performing items like Blouses, Pants, and Jewelry to cross-sell underperforming outerwear categories.