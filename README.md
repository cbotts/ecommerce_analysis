# Analysis of Ecommerce Sales 
A time series analysis of Ecommerce data 

## Objective
Make investment recommendations for the Ecommerce company based on predicted sales margins 

## How to Run 
```
gh repo clone cbotts/ecommerce_analysis
jupyter notebook Botts_Rodriguez_Final.ipynb
```

## Data 
Data includes sales transactions from a UK based online retailer presented in transactional format.

**Data Dictionary** 

- Order Date          - the date the transaction took place 

- Order ID            - unique id for one customer order

- Product             - product name 

- Quantity Ordered    - the number of the product order in a transaction 

- Price Each          - the price of the one product 

- Cost price          - the cost of the one product for the company 

- turnover            - quantity of products ordered x cost of the product

- Product_ean         - the price of the one product 

- catégorie           - the type of product 

- Purchase Address    - location to which the product shipped 

- margin              - profit 

## Methods
Multiple ARIMA models were built to capture various subsets of the data and hyperparameters were calculated with AutoARIMA. Train/test splits was made along the time axis to evaluate the quality of the models. 

## Conclusion 
Each of the models had a good fit for the data. Predicted sales values were flat with a very slight decline. These models do not appear to accurate predict very far into the future. 

