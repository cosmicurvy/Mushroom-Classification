**🍄‍🟫 Mushroom Classification: Edible or Poisonous?**

**Overview**

This dataset includes description of hypothetical samples corresponding to 23 species of grilled mushroom in the Agaricus and Lepiota Family. Each species is classified as either definitely edible or definitely poisonous. 

The primary goal is to use the provided characteristics to predict the classification of a mushroom. This is a classic binary classification problem frequently used for beginner to intermediate machine learning projects. 

**Dataset Information**

Source: UCI Machine Learning Repository via Kaggle
Instances: 8,124
Features: 22 physical characteristics (categorical)
Target: class (edible=e, poisonous=p)

**License**
This dataset is in the public domain under CC0: Public Domain. 

**Key Insights And Chalenges**
Data Quality: This dataset is notably clean with no missing values though '?' values exist in the 'stalk-root' feature. 
High Correlation: Some features are extremely strong predictors of poisonous vs edible.

**Project Objectives**
The primary objective is to develop a robust classification model that can distinguish between edible vs poisonous mushroom. Beyond simple prediction, the project focuses on feature visualization and dimensionality deduction techniques like Chi-Square. 