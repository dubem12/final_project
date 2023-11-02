# Final Project

## Dataset Details:
The dataset consists of information on 22,000 properties in Washington D.C. This dataset contains historic data on houses sold between May 2014 and May 2015.

## Objective:

Price Prediction Model: The primary objective was to build a data model capable of predicting the price of a house based on selected features.<br>
Feature Importance for High-Value Houses: Additionally, the management team was interested in identifying the features that are most important for houses priced above $650,000.<br>
<br>

## Data Features:
The dataset includes various features related to the properties, including: <br>

1. Property ID 
2. Date the house was sold
3. Property price 
4. Waterfront view
5. View grade
6. House condition (ranging from 1 indicating worn-out to 5 indicating excellent)
7. Grade according to the King County grading system (ranging from 1 for poor to 13 for excellent)
8. Square footage of the house without including basement
9. Square footage of the basement
10. Square footage of the living room as of construction
11. Square footage of the living room as of 2015 (implying renovation)
12. Square footage of the land/lot as of 2015 (implying renovation)
13. Longitude and latitude of the houses

## Tools Used:
The following tools were employed in the analysis of the dataset:

1. Python with all necessary libraries stored ina requirements.txt file for data manipulation, modelling and analysis
2. Tableau for data visualization, enabling the creation of interactive and insightful visualizations to aid in data exploration and presentation.
   
## Models Used:
Two different models were employed in this analysis:

1. Linear Regression: A commonly used model for predicting numerical values, which attempts to find a linear relationship between the features and the target variable (house price).
2. Decision Tree: A decision tree model was utilized, which is a non-linear model that can capture complex relationships in the data.
   
## Best Performance Model Summary:
The Decision Tree model outperformed other models in terms of predictive accuracy. It provided superior results, as measured by evaluation metrics such as accuracy, mean squared error, or other relevant metrics. The specific scores or metrics can be provided to give a more detailed summary.

## Future Outlook:
In future iterations of this analysis:

Further Exploration of Zipcodes: More comprehensive exploration and feature engineering for zipcodes could be considered. Certain factors, such as crime rates, neighborhood characteristics, proximity to private and social amenities, industrial clusters, and other local factors, can significantly influence housing costs. Incorporating these variables into the analysis can enhance the model's predictive accuracy. <br>

Additional Modeling Techniques: Apart from Linear Regression and Decision Trees, other machine learning models such as K-Nearest Neighbors (KNN) could be explored for performance comparison. Different models may capture unique patterns and relationships in the data that were not identified by the initial models, leading to potentially improved predictive accuracy.