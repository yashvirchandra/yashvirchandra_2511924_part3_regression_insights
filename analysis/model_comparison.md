# Model Comparison

## Model 1: Simple Regression (Marketing Spend)

**Dependent Variable:** Monthly Sales

**Independent Variable:** Marketing Spend

This model shows a positive relationship between marketing spend and monthly sales. Higher marketing investment is generally associated with higher sales. However, the model only considers one variable and does not account for other important business factors.

---

## Model 2: Simple Regression (Footfall)

**Dependent Variable:** Monthly Sales

**Independent Variable:** Footfall

The results show that stores with higher customer footfall usually achieve higher monthly sales. Customer visits are an important indicator of sales performance, but this model ignores inventory, regional differences and other operational factors.

---

## Model 3: Multiple Regression

**Dependent Variable:** Monthly Sales

**Independent Variables:**

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Region Dummy Variables

### Model Performance

* R² = 0.8114
* Adjusted R² = 0.8078

The model explains approximately 81.14% of the variation in monthly sales.

### Significant Variables

* Marketing Spend
* Footfall
* Inventory Availability Percentage
* Region East

### Variables with Weak Statistical Evidence

* Region North
* Region West

### Business Usefulness

The multiple regression model provides the best understanding of monthly sales because it evaluates several business factors together. It is the most useful model for supporting management decisions.

### Limitations

Regression analysis measures association between variables but does not prove that one variable directly causes another. External factors such as market competition, seasonal demand and customer preferences are not included in the model.

## Final Model Selection

The multiple regression model was selected as the final model because it has the highest explanatory power and provides the most reliable insights for business decision-making.
