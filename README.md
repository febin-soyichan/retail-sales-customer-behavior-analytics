# Retail Sales & Customer Behavior Analytics

## Project Overview
This project analyzes retail transaction data to evaluate customer buying behavior, predict sales outcomes, and segment buyers for targeted marketing strategies. Using Python for data processing and predictive modeling, alongside Power BI for visual analytics, the solution provides actionable business insights to drive operational performance.

## Tools & Technologies
* **Language:** Python
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest Regressor, K-Means Clustering)
* **Visualization:** Power BI, Matplotlib, Seaborn

## Key Milestones & Workflow
1. **Data Preprocessing & Cleaning:** Processed 1,000+ retail transaction records using Pandas, handling missing values, standardizing dataset attributes, and engineering features (date dimensions and demographic age groups).
2. **Customer Segmentation:** Applied K-Means Clustering to group customers into 4 distinct behavioral segments based on purchasing habits (`total_amount`, `quantity`).
3. **Predictive Modeling:** Built and evaluated a Random Forest Regression model using `scikit-learn` for revenue prediction.
4. **Dashboard Development:** Created an interactive, multi-page Power BI dashboard to track key performance metrics, product category distributions, and demographic trends.

## Business Logic & Analysis

### Key Insights (What the data tells us)
* **Top Revenue Sellers:** Sales are spread fairly evenly across categories, but **Electronics** brings in the most money ($156.9K), followed closely by **Clothing** ($155.5K) and **Beauty** ($143.5K).
* **Who Spends More:** Female shoppers spend slightly more overall ($233K) than male shoppers ($223K). The **46–55 age group** is the highest-spending demographic ($100.7K).
* **4 Types of Shoppers:** Customer segmentation grouped buyers into 4 distinct behavioral types based on purchase volume and spending habits.

### Underlying Causes (Why this is happening)
* **Generic Marketing:** The business treats all customers the same instead of giving special offers to the highest-spending age group (ages 46–55).
* **No Reason to Return:** Low-spending customers usually buy once and leave because there are no rewards or package deals to encourage a second purchase.

### Recommended Solutions (What to do next)
* **Target High Spenders:** Create exclusive deals or premium loyalty rewards for the 46–55 age group.
* **Offer Product Bundles:** Pair electronics with lower-cost accessories (e.g., Electronics + Accessories) to encourage low-spend customers to buy more per visit.
