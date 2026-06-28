# Model Equations

## Simple Regression Model 1

Monthly Sales = Intercept + β₁(Marketing Spend)

The marketing spend coefficient represents the expected increase in monthly sales for each additional unit spent on marketing.

---

## Simple Regression Model 2

Monthly Sales = Intercept + β₁(Footfall)

The footfall coefficient represents the expected increase in monthly sales as more customers visit the store.

---

## Multiple Regression Model

Monthly Sales =
153400.80

* 1.186 × Marketing Spend
* 33.87 × Footfall
* 2818.21 × Inventory Availability Percentage
  − 11393.11 × Region North
  − 21940.49 × Region East
  − 4449.12 × Region West

## Dummy Variable Explanation

The Region variable was converted into dummy variables.

The South region was used as the reference category. Each region coefficient compares that region with South while keeping all other variables constant.

## Coefficient Interpretation

Marketing spend, footfall and inventory availability have positive coefficients, indicating that increases in these variables are associated with higher monthly sales.

Region East has a negative and statistically significant coefficient, suggesting that stores in the East region generally achieve lower monthly sales than stores in the South region.

Region North and Region West have negative coefficients but are not statistically significant, so these differences should be interpreted carefully.

## Final Model

The multiple regression model was selected because it explains approximately 81% of the variation in monthly sales and provides the strongest overall business insights.
