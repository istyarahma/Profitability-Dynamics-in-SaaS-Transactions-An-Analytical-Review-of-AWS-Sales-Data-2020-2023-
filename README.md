# Profitability Dynamics in SaaS Transactions: An Analytical Review of AWS Sales Data(2020-2023)

## Background
The global SaaS landscape has evolved rapidly, with Amazon Web Services (AWS) emerging as a dominant enabler. As SaaS demand surges, not all transactions are profitable—despite high sales volumes. This analysis explores the underlying factors driving negative profit in AWS SaaS transactions.

## Goal
To identify key variables that influence profit outcomes in AWS SaaS sales and provide data-driven recommendations for improving profitability through pricing and discount optimization.

## Business Problem Statements
- What proportion of AWS SaaS transactions yield negative profit?
- How have sales and profit trends evolved from 2020 to 2023?
- Which variables (e.g., discount rate, region, segment) are significantly associated with negative profit?
- How can AWS improve its discount strategy across segments and product lines?

## Dataset Overview
- Source: [Kaggle - AWS SaaS Sales Dataset](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales)
- Type: AWS SaaS sales transactional data
- Period: 2020–2023
- Number of transactions: 9994
- Initial variables: 19
- Post-cleaning variables: 17 (redundant and irrelevant columns dropped)
- Final variable count: 22 columns
- Added columns: 5 new variables were engineered for analytical purposes:
    - `Sales Category` (e.g., low/medium/high)
    - `Profit Category` (e.g., negative/positive/zero and negative/positive)
    - `Price` (calculated per unit)
    - `Profit Margin` (profit relative to sales)


## Analytical Approach
The project employs:
- **Univariate analysis** for distributional insights
- **Bivariate analysis** using correlation, chi-square, ANOVA, and t-tests
- **Multivariate analysis** via multiple logistic regression to evaluate adjusted effects on profit outcomes

## Key Findings (Summary)
- A significant number of high-sales transactions result in negative profit
- Discounts and quantity ordered are strong predictors of profit loss
- Region and customer segment also show significant associations with profitability

## Recommendations
- Refine discount strategy by segment and product category
- Monitor high-quantity, low-margin transactions
