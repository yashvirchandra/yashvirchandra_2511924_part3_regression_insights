# Part 3: Regression-Based Business Insights & Model Interpretation

## Business Problem

The objective of this project is to identify the factors that are most strongly associated with monthly sales across retail stores. Using regression analysis, the project helps management understand how different business variables influence sales and supports better business decision-making.

## Dataset Description

The dataset contains information for 320 retail stores. It includes monthly sales, marketing spend, customer footfall, inventory availability, customer ratings, average discount percentage, staff count, store region and store type.

### Dependent Variable

* Monthly Sales

### Independent Variables

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Average Discount Percentage
* Customer Rating
* Staff Count
* Region

### Numerical Variables

* Monthly Sales
* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Average Discount Percentage
* Customer Rating
* Staff Count

### Categorical Variables

* Region
* Store Type

## Data Preparation

The original dataset was preserved in a separate worksheet. Data was cleaned before analysis and dummy variables were created for the Region variable.

The South region was used as the reference category to avoid the dummy variable trap.

## Regression Approach

Two simple regression models were created using Marketing Spend and Footfall as independent variables. A multiple regression model was then developed using Marketing Spend, Footfall, Inventory Availability Percentage and Region dummy variables.

## Model Comparison Summary

The multiple regression model performed better than both simple regression models.

* R² = 0.8114
* Adjusted R² = 0.8078

The model explains approximately 81% of the variation in monthly sales.

## Final Model Selected

The multiple regression model was selected because it includes multiple business drivers and provides the strongest explanatory power.

## Business Recommendation

The results indicate that marketing spend, customer footfall and inventory availability are the strongest factors associated with monthly sales. These areas should receive the highest priority when making business decisions.

## Assumptions and Limitations

Regression identifies statistical relationships but does not prove causation. Other business factors such as competition, seasonal demand and local events may also influence sales but are not included in the model.

## Screenshots Included

* Simple Regression Output
* Multiple Regression Output
* Residual Analysis
* Model Comparison
