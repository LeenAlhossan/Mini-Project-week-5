# Mini-Project-week-5
In this project, I applied the Week 5 feature engineering workflow on a dataset containing:
price
sqft
rooms
Steps Performed
Created a domain-driven feature:
price_per_sqft = price / sqft
Compared variance between raw and engineered features.
Computed the correlation matrix to analyze relationships.
Applied Variance Threshold to remove low-variance features.
Removed highly correlated features (threshold = 0.9).
Checked for potential target leakage.
If the target variable is price, then price_per_sqft causes data leakage because it is derived from the target.
Conclusion
This project follows the structured pattern:
Domain Feature → Correlation → Feature Selection → Leakage Check
