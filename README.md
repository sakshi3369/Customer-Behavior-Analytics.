# E-Commerce Customer Purchase Pattern & Retention Analysis.
This project focuses on extracting actionable business intelligence from an e-commerce dataset containing 60,000 transactions. The primary goal is to analyze customer purchasing patterns and retention lifecycle,combining Market Basket Analysis (Apriori Algorithm) to provide data-driven recommendations for increasing customer lifetime value (CLV).


🚀 Key Objectives
Predict Churn: Identify "at-risk" customers based on their last activity.

Discover Product Affinities: Find which products are frequently bought together to improve cross-selling.

Analyze Retention: Visualize customer loyalty lifecycles using cohort heatmaps.

📈 Project Workflow
1. Data Preprocessing & EDA
Cleaned and structured a dataset of 60,000 entries featuring event_time, product_id, category_code, and price.

Grouped transactions at the user level to calculate Total Spent, Total Events, and Recency.

2. Customer Retention Analysis
Churn Labeling: Created a logic to flag users as "churned" if they haven't made a purchase in over 30 days.

Cohort Heatmap: Developed a retention matrix to track monthly cohorts, allowing us to see exactly when customers stop returning to the platform.

3. Market Basket Analysis (Apriori)
Utilized the Apriori Algorithm to identify association rules between product categories.

Calculated Support, Confidence, and Lift to determine which product pairings are statistically significant, providing a roadmap for better product bundling.

4. Customer Segmentation
Implemented K-Means Clustering to segment customers into distinct groups (e.g., Champions, At-Risk, New Users) based on their purchasing behavior.

Business Insights & Impact
Optimized Marketing: By identifying churn patterns, the business can trigger automated "Win-back" emails exactly when a cohort begins to drop off.

Increased AOV: Suggesting "frequently bought together" items at checkout based on the Apriori rules can directly increase Average Order Value (AOV).

Inventory Planning: Understanding category-level affinities helps in better stock management and promotional planning.
