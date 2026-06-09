📊 End-to-End Customer Behavior & Revenue Analytics Pipeline

📖 Project Overview
This project establishes a complete data engineering and analytics pipeline to evaluate customer purchasing patterns, subscription structures, and revenue distributions. Utilizing a dataset of 3,900 distinct customer transactions, the pipeline transitions raw data through programmatic cleaning, relational database engineering, and executive-level business intelligence dashboards to uncover actionable retail insights.

🛠️ Technical Architecture & Tool Stack
Data Cleaning & Engineering (Python / Pandas): Profiling data structures, verifying integrity constraints, handling schema typing, and validating that the dataset contains zero null fields.

Database Management & Querying (PostgreSQL / pgAdmin): Designing relational database schemas, establishing an automated data ingestion pipeline via SQLAlchemy, and executing advanced window functions (DENSE_RANK()) alongside complex aggregations for behavioral segmentation.

Business Intelligence & Visualization: Building a centralized, interactive user dashboard tracking key macro-metrics including total customer volume, average order values ($59.76), and average product feedback ratings (3.75).

📈 Executive Strategic Insights
Demographic Value Drivers: The 20-29 age demographic represents the highest grossing consumer group, leading both transaction volume and total revenue generation across all categories.

Product Category Dominance: The Clothing segment serves as the primary operational driver, significantly outpacing Accessories, Footwear, and Outerwear in both sheer sales volume and gross revenue contribution.

Subscription Optimization: Clear demographic benchmarks separate repeat purchasers (>5 historical orders) from regular buyers, offering a direct data foundation for targeted loyalty and subscription conversion campaigns.

📂 Repository File Layout
Customer_shopping_anlysis.csv.xls — Raw underlying consumer transaction ledger.

Customer_Shopping_Behaviour_Analysis.ipynb — Production-ready Python cleaning pipeline and automated PostgreSQL connection script.

customer_behavior_analysis.sql — Optimized SQL scripts containing operational window functions and business queries.

dashboard.png.png — High-resolution preview of the interactive executive business intelligence layout.
