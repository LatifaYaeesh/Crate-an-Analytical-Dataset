# Create-an-Analytical-Dataset
<h2> The Business Problem </h2>

Pawdacity is a leading pet store chain in Wyoming with 13 stores throughout the state. This year, Pawdacity would like to expand and open a 14th store. Your manager has asked you to perform an analysis to recommend the city for Pawdacity’s newest store, based on predicted yearly sales.  

Your first step in predicting yearly sales is to first format and blend together data from different datasets and deal with outliers.  

<h2> Your manager has given you the following information to work with: </h2>
  
  The monthly sales data for all of the Pawdacity stores for the year 2010.
  NAICS data on the most current sales of all competitor stores where total sales is equal to 12 months of sales.
  A partially parsed data file that can be used for population numbers.
  Demographic data (Households with individuals under 18, Land Area, Population Density, and Total Families) for each city and county in the state of Wyoming. For people who are unfamiliar with the US city system, a state contains counties and counties contains one or more cities.
  Map of Wyoming Counties 
  
  <h2> Steps to Success Step 1:</h2>
  
  <h2> Business and Data Understanding: </h2>
  Your project should include a description of the key business decisions that need to be made. 
  
  <h2> Step 2: Building the Training Set To properly build the model, and select predictor variables, create a dataset with the following columns: </h2>
  
  City 2010 Census Population Total Pawdacity Sales Households with Under 18 Land Area Population Density Total Families  
  This dataset will be your training set to help you build a regression model in order to predict sales in the Practice Project in the next lesson. 
  Every row should have sales data because we're trying to predict sales. 
  
  <h6>Notes: </h6>
  You should be consolidating the data at the city level and not at the store level. 
  We only have data at the city wide level so any analysis at the store level will not be sufficient to complete this analysis. 
  We simply need to focus on cleaning up and blending the data together in this step.  
 If you’ve done everything correctly, 
 
 <h6> the sum for each of the above columns should be: </h6>
 
 -<h6> Census Population: </h6> 213,862 
- <h6> Total Pawdacity Sales: </h6>3,773,304 
 - <h6> Households with Under 18:</h6>34,064 
 - <h6> Land Area: 33,071 
  -<h6> Population Density: </h6> 63 
  <h6> Total Families: </h6> 62,653 with 11 rows of data
