Objective: Analyze the bank's loan data to derive actionable insights and recommend target customer segments for loan approvals.

Data:https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter/data

Data Processing and Analysis Techniques:
Data Cleaning: Handled missing values, detected and treated outliers, and performed value modifications.
Data Manipulation: Conducted feature selection and engineered new features to improve model accuracy.
Data Visualization: Utilized Python visualization libraries like Matplotlib and Seaborn to create insightful visualizations.
Binning: Categorized continuous variables into discrete bins for better analysis.
Feature Selection: Identified and selected the most significant features impacting loan defaults.
Missing Imputations: Imputed missing values to maintain data integrity.
Outlier Detection and Treatment: Identified and treated outliers to ensure data consistency.
Data Analysis: Performed both univariate and bivariate analysis to understand the relationships between variables.
Conclusion and Insights:
Cash Loans: The majority of customers have taken cash loans, which are less likely to default.
Gender: Most loans are taken by females, with a lower default rate (~7%) compared to males.
Marital Status: Married individuals have an 8% default rate, making them a safer target.
Income Type: The safest segments include working individuals, commercial associates, and pensioners.
Occupation: Drivers have the highest default rate, while accountants, core staff, managers, and laborers have default rates ≤10%.
Housing: Individuals with a house/apartment have an ~8% default rate.
Education: Highly educated individuals have a default rate <5%.
Goods Price: Most loans were given for goods priced between 0 to 1 million.
Credit Amount: Most loans are for credit amounts of 0 to 1 million.
Annuity Payment: Most customers are paying annuities between 0 to 50K.
Income: Most customers have incomes between 0 to 1 million.
Bivariate Analysis:
Credit and Goods Price: AMT_CREDIT and AMT_GOODS_PRICE are linearly correlated. As AMT_CREDIT increases, the default rate decreases.
Income and Loan Amount: People with incomes ≤1 million taking loans ≤1.5 million are less likely to default.
Children: Individuals with 1 to less than 5 children are safer loan candidates.
Annuity: Those able to pay annuities up to 100K, for loans up to less than 2 million, are considered safer.
Analysis on Merged Data:
Repair Purposes: Most previous applications for repairs had high cancellation rates.
Repayment: Customers with canceled or refused previous applications are likely to repay current loans.
Unused Offers: High-income band customers who previously had unused offers now have a higher default rate.
Bank Target Recommendations:
Demographics: Prefer customers with low income (below 1 million), highly educated, married, having a house/apartment, and with children not exceeding five.
Occupation: Target individuals working as accountants, core staff, managers, laborers, and those working in organizations like Others, Business Entity Type 3, and self-employed.
Gender: Preferably female customers.
Unaccompanied Individuals: Default rate is ~8.5%, making them relatively safer.
Amount Segment Recommendations:
Credit Amount: Should not exceed 1 million.
Annuity: Set around 50K, depending on eligibility.
Income Bracket: Below 1 million.
Previous Cancellations/Refusals: 80-90% of customers previously canceled/refused are repayers. Banks should consider this segment for loans.
