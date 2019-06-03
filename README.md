# Kaggle-Kickstarter-2018-Analysis

# Hackwagon's DS102 Project
This project was a joint effort between me and my cousin, Chong Jun Guo, for our Hackwagon's DS102 project.

# Executive Summary
As technology is advancing, we believed that technology projects has a very high chance of success (>50%). However, we found that this is not true even when we investigate the sub categories within Technologies.

We would also like to look into what are the attributes that will make a kickstarter project succeed. However, other than the pledged and goal amount, Country, Main category and Sub category are not important features in predicting the success of a Kickstarter Project. This was evident by our charts below and feature importance analysis.

# Data source
https://www.kaggle.com/kemical/kickstarter-projects#ks-projects-201801.csv

# Data preparation
1) Created dummy variables for main category, sub category & country
2) 80% Training and 20% Testing split
3) Standardizing of features
4) Created AUC graph to check what's the best depth to prune the tree

# Chosen Model
Decision Tree

# Conclusion based on EDA & Decision Tree Model
Therefore, we can conclude that the category of the project does not determine the success of the project. 82% of the time, the amount of money pledged determines how successful the project. 
The remaining 18% of the time, how successful the project is will be based on the amount of money the user has set to target. 
Country, Main category and Sub category are not important features in predicting the success of a Kickstarter Project. This was also evident by our charts above.
