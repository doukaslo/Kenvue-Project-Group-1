# Kenvue-Project-Group-1
MGTC28 Kenvue Project: Optimizng Trade Spend
Project Plan

How will we approach this problem?:

	We will approach this project from the perspective of answering our main question: How can Kenvue optimize their trade spend (promotion $) for one of their 6 Need States? 

Step #1: The first stage in answering this question is to organize and clean the data Kenvue provided for all 6 of their Need States. Once we have organized the data, we will be able to analyze the Need States and determine if there are seasonal trends in sales, inventory, and trade spending. All of our analysis will be visualized through tools that we have learned in class. 

Step #2: Once we have determined seasonal trends across those 3 facets, this will guide our decision on which singular Need State we feel can benefit from further optimization. Whichever Need State is chosen, we will conduct further analysis by:
Creating a time-series forecasting model to predict future sales
Conduct demand forecasting using time-series decomposition. 
Analyzing the trade spend data for any potential opportunities for optimization. 

Through this analysis, we believe we will be able to answer critical questions that are important when determining the trade spend mix such as what are the market demand trends for this specific Need State? Which season would be considered appropriate timing to increase trade spending? 

Step #3: When we have the answers to these questions we will be able to provide a clear recommendation on how Kenvue can optimize their trade spend for the chosen Need State as well as be able to outline overall trends across all 6 need states. 

Our Group: Our group consists of Louis Doukas, Anvitha Ivernad Sathyashankar, and Thushshan Rameswaran. We plan to have an equal division of labor with each of us being assigned a portion of the technical analysis in step #2 giving us all a chance to apply what we have learned in class. We will each be in charge of visualizing the analysis topic we were in charge of on the presentation slides.

The Data: We believe that there is insight to be gained from all of the data sets, but due to our specific goal of analyzing seasonal trends in sales, and optimizing trade spend. The most important data sets for us will be: “Total Sales”, and “Total Trade Spend”. We will also probably use the “Factory POS$” and “Ecomm POS $” in our seasonal trend analysis. We do not feel that inventory analysis will provide much value to answer our specific question.

Libraries: pandas, seaborn, seasonal_decompose from statsmodels.tsa.seasonal, ExponentialSmoothing from statsmodels.tsa.holtwinters


External Factors
Kevenue’s most popular products such as Band-aids or Listerine, whose main ‘need state’ is health and hygiene appear to be all-season products. However, latest drug store news reveals that seasonality trends have been shaping the future of the personal care market. Therefore, while performing a multivariable regression, these trends need to be accounted for to increase the accuracy of the model. 


Pseudocode:

Import necessary libraries, such as mathplotlib, pandas, seaborn, and
Load and clean datasets
Drop any empty datapoints
Add a new column for “Season” and encode seasons
Visualize trends in need state 
Build time a time-series forecasting model
Use simple time-series decomposition 
Predict future sales using the forecasting model and using OLS regression
Create a demand-forecasting model using time-series decomposition
Analyze trade spend data for optimization 
Identify patterns and relationships between trade spend and sales
Display forecasted results and relevant visualizations
