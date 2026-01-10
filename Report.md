 Supermarket Sales Analysis Report

Project: Advanced Python Project (First Semester 2025/2026)  
Date: December 29, 2025

 1. Objective
The goal of this project was to analyze historical supermarket sales data to understand sales trends, customer behavior, and product performance. We utilized Python libraries including Pandas, NumPy, Matplotlib, and Seaborn for data manipulation and visualization.

 2. Data Overview
- Dataset Source: SuperMarket Analysis.csv
- Size: 1000 records, 17 columns.
- Data Quality: The dataset was found to be clean with no missing values. Date and Time columns were converted to appropriate formats for time-series analysis.

 3. Key Findings

 Q1: Which Branch has the highest sales?
Answer: Giza
- Giza: $110,568.71
- Alex: $106,200.37
- Cairo: $106,197.67
*Observation: Sales are distributed relatively evenly across the three branches, with Giza taking a slight lead.*

 Q2: Which payment method is the most popular?
Answer: Ewallet
- Ewallet: 345 transactions
- Cash: 344 transactions
- Credit card: 311 transactions
*Observation: Electronic wallets and Cash are almost equally preferred, while Credit Cards are slightly less common.*

 Q3: Is there a relationship between Sales and Rating?
Answer: No significant relationship.
- Correlation Coefficient: -0.036
*Observation: The customer rating (satisfaction) does not seemingly depend on the transaction value (sales amount).*

 Q4: At what time do people buy the most?
Answer: 19:00 (7 PM)
- The peak sales hour is 7:00 PM, generating nearly $40,000 in sales.
- Other busy hours include 1:00 PM (13:00). The late evening wave is the most significant.

 Q5: Which product line performs the best?
Answer: Food and beverages
- Food and beverages: ~$56,145
- Sports and travel: ~$55,123
- Electronic accessories: ~$54,338
*Observation: Food and beverages is the top-performing category, but Sports, Electronics, and Fashion are very close behind. Health and beauty is the lowest performing category (~$49,194).*

 4. Conclusion
The analysis reveals a healthy distribution of sales across branches and product lines. To maximize revenue, marketing efforts could be targeted during the 7 PM peak hour and focused on promoting Health and beauty products to bring them up to par with other categories. The payment infrastructure must robustly support both Ewallets and Cash.
