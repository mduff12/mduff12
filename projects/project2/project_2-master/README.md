# Meryl Duff: Ames Housing Regression Analysis
## Executive Summary

The Ames housing dataset is a intriguing database of housing prices and characteristics from the city of Ames, Iowa. Along with the most common characterstics associated with real estate pricing, it has a diverse range of elements. From masonry veneer type, to roof material, to basement finishing and electrical systems - it may feel intimidating to try and pick apart. That is why I have produced a regression model that takes the most important aspects of a house and uses them to predict housing prices. 

# ![](Images/370px-Ames_Montage.jpg)


**Overall, my analysis indicates that the following characteristics will help us to successfully predict sales prices:**
Overall Quality (a proprietary score of the overall material and finish of the house)
Above grade (ground) living area square feet
Total square feet of basement area
Size of garage in car capacity
Year Built
Remodel date
Full bathrooms above grade

**Additionally, the following characteristics helped narrow down the model so we were able to more accurately predict prices:**

Garage location: Attached to home
Garage Quality: Typical/Average
Basement Exposure (Refers to walkout or garden level walls): Good 
Basement Finish: Good living quarters


## How to Use these Models
1. Run each notebook in the 'Coding' folder in the order that is indicated in the title
2. Notebook 1 contains the data cleaning and exploratory data analysis
3. Notebook 2 contains the baseline linear regression model and cross validated linear regression.
4. Notebook 3 contains the feature engineering (polynomial features) and multiple linear regression on engineered features.
5. Notebook 4 contains the Ridge and Lasso Regressions. This notebook helps us understand how the features interact and what is less/more important for sale price. 
6. At the bottom of the relevent notebooks there is a "Kaggle Submissions" section, if you are participating in the Kaggle challenge

 

# Analysis & Recommmendations
When it comes to housing and real estate, there are many factors that could indicate sale price. The features that were correlated to the final sale price in the Ames housing data set include *Overall Quality Score* and *above grade (ground) living area square feet*. It is no surprise that feature which aggregates all of the aspects of a house is most strongly correlated with price. Similarly, above ground square footage and basement square footage may be easy-to-guess variables, too. 

However, the basement finish is also a feature that matters, and having "good living quarters" and "good" exposure will help predict the sale price. The more cars that can fit in the garage the better, but having a garage attached to the home is also important. Surprisingly, garage quality could be average - but having it attached to the house and the number of cars it can fit are also important factors. 

There are some characteristics of the house that, when combined, helped us to predict the sale price. These combined features proved to be important to final sale price:

Overall Quality score & above ground living area square feet
Total Basement Square Feet & number of cars that can fit in the garage
Total Basement Square Feet & good quality living quarters
Number of full bathrooms & good basement exposure

Because the overall quality score has evident impact on sale price, I looked into the correlation of this feature to the other features in the dataset. Important factors to overall quality include: 

**Year Built
Year Remodeled
Total Basement Square Feet
Above Ground Living Area Square Feet
Size of garage in car capacity**


Based on the insights gathered through our analysis, we can conclude that housing prices in Ames, Iowa can be successfully predicted with the above detailed features. For potential home owners looking to see or buy, it would be prudent to keep in mind these features when evaluating your budget and the price the home is worth. For realtors or sales professionals, these features (and the continuing list of interactive features and their coefficients in notebook 4), can help price homes to their value. Finally, for contractors or construction companies, this data would be invaluable in building new homes. 