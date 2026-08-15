# What Drives the Price of a Used Car?

## Summary
This project analyzes a dataset of 426,000 used car listings to identify the key 
factors that influence used car prices. Using the CRISP-DM framework, we cleaned 
the data, engineered features, and built three regression models (Linear Regression, 
Ridge, and Lasso). Ridge Regression performed best with an RMSE of 0.59 on a log scale.

**Key findings:**
- Condition is the strongest driver of price — salvage and fair condition cars lose significant value
- Luxury brands (Ferrari, Porsche, Tesla, Aston-Martin) command large premiums
- Clean title, lower mileage, and newer age all positively impact price

## Recommendations
Dealers should prioritize clean-title, good-to-excellent condition inventory under 
10 years old and under 100,000 miles. Avoid salvage titles.

## Notebook
[View the full analysis here](prompt_II.ipynb)

## Dataset
Source: Kaggle — 426K used car listings (subset of 3M)

## Libraries Used
pandas, numpy, matplotlib, seaborn, scikit-learn
