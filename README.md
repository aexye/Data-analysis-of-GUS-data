A project to analyze data from the Central Statistical Office (GUS). Two files containing variables such as:

- population, 
- unemployment,
- enrollment,
- income,
- expenses
- groceries,
- equipment at home.

Variables are broken down by year and presented by different units depending on the category.

# Project structure - table of contents

1. Importing libraries 
2. Loading data
3. Data cleaning

 3.1 gminy.csv file
   - Unique values of the "Category" column
   - pivot_table() to better illustrate the relationship of "Category" and "Variable" columns
   - Missing data (NaN)
   - Breakdown of the data frame relative to the "Category" column
   - suspicious values

 3.2 ludnosc.csv file
    - analogously as in section 3.1

4. Data analysis

 4.1 Linear regression
 - Question 1: Is spending linearly correlated with income, Does spending depend on income?
 - Question 2: Does consumption of alcoholic beverages and tobacco products depend on the receipt of the 500+ benefit?
 - Question 3: Will health spending depend on disposable income?

Linear regression for question 3.
    
 4.2 Decision tree
 - Tree proposal 1: Expenses, Income -> Unemployment.
 - Proposition tree 2: Income per capita, population per km2, Education spending -> Scolarization

 4.3 Analysis of the distribution of the variable
 - Average monthly expenditures from 2016 to 2020

 4.4 K-Means algorithm
 - Unemployment, income
