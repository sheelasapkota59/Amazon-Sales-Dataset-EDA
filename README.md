Amazon Sales Data Analysis
Overview

This project explores and analyzes an Amazon Sales Dataset to gain insights into product categories, pricing trends, customer reviews, and sales patterns.
Objectives

    Clean and prepare the dataset for analysis.
    Explore product pricing, discounts, and ratings.
    Visualize data patterns to detect trends.
    Handle missing values and outliers in the dataset.
    Perform feature encoding for model preparation.

Dataset

    Source: Amazon Sales Dataset (example: sourced from Kaggle or another public repository).
    Size: 1465 rows, 16 columns.
    Columns:
        product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, img_link, product_link

Key Steps
1. Data Cleaning

    Converted non-numeric columns (e.g., discounted_price, actual_price) to numeric types after removing special characters.
    Handled missing values by imputing the median for rating_count.

2. Exploratory Data Analysis (EDA)

    Used descriptive statistics and visualizations (scatter plots, histograms) to understand product pricing and rating trends.
    Detected and corrected invalid or missing data.

3. Data Transformation

    Categorical features like product_id, category, review_id, and others were label-encoded to prepare for machine learning models.

4. Data Visualization

    Visualized correlations between numerical variables like discounted_price, actual_price, rating, and rating_count using a heatmap.
    Examined the distribution of actual prices and relationship between actual_price and rating.

Technologies Used

    Programming Language: Python
    Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
    Jupyter Notebook: For code execution and visualization

Results

    The dataset showed a strong correlation between actual prices and discounts.
    Categories with higher discounts tended to have better ratings.
    Insights from product categories can guide pricing strategies and marketing decisions.
