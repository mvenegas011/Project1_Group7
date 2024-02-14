# Project1_Group7

# Project Team
Anup Pathak, Dharmesh Gautam, Melisa Venegas, Sandeep Kothapalli

# 1. About the Project
The project aims to analyze the housing data, understand the trends, and develop forecast for the next 12 month period. The code was developed in Jupyter and Google Colab and present the steps the team took to draw insights from the data. The team utilized the most relevant technical aspects of Python libraries and use of Prophet to address the analytical requirements of the project.
The housing data was collected from Redfin website. Redfin is a real estate brokerage with direct access to data from local multiple listing services, as well as insight from their real estate agents across the country. This data summarize the monthly housing market for every State, Metro, and Zip code in the US from 2012 to 2023. 

### Dataset
The dataset for the project was sourced from this public URL: https://www.redfin.com/news/data-center/ 

### Data Dictionary
The definition of various terms / columns used in the dataset is published at this URL: https://www.redfin.com/news/data-center-metrics-definitions/

### Tools for analysis
1. Jupyter Notebook
2. Google Collab [https://colab.google/]
3. Github for code repostory 

# 2. The Approach

### Data Management
The raw data was downloaded from the original source into a tab separated values for the initial analysis. The original data file size was significantlly large making it difficult to perform the analysis, given the limitations of the free tools. After a quick review of the data, the initial file was reduced in size by selecting the most relevant features required for the analysis. The new layout was stored as a standard CSV file which served as an input for the rest of the analysis.

### Analysis Approach
1. Undersand the raw data by profiling the data and reviewing the published data dictionary
2. Identify opportunities for analysis and prediction (See below)
3. Prepare data for analysis by reading relevant data using Pandas
4. Identify trends in data by using Matplotlib libraries 
5. Seek insights from the data
6. Predict trends using Google's Colab and 'Prophet'
7. Draw conclusions

### Focus areas for analysis
While the project team found the data rich for analysis, given the time and project constraints, the team focused their efforts on the following areas: 
1. National trends across all metro areas for number of homes sold and home prices, by property types, across all periods
2. Top 5 Metro markets for the recent period, 2023
3. Trends in Top 5 metro markets for homes sold and home prices by property types across all periods
4. Seasonality in the homes sold across all metros and across the period over a 12 month cycle
5. Curve fitting and prediction for the next 12 month period for single family homes across all metro areas

While we used top 5 metro areas or all metro areas for analysis to showcase some of the analytical capabilities in this project, we can extend this approach to analyze and predict for any region or group of metros, depending on the business need.

### Missed opportunities
Given the time constraints, we could not use the data for expanding our analysis for correlation studies. We also wanted to study the impact of Covid on the housing market, but could not do so at this time. We leave these analyses for a separate endeavor.

In order to expand our study of coorelation between important variables, we would need additional data sources, such as demographic, income, or census data, to supplement the real estate market data.

# 3. The Solution
The solution has been uploaded to the Github into the project repo. It can be found here: https://github.com/mvenegas011/Project1_Group7.

It primarily consists of three parts:
1. Ingesting the initial raw data <Project1-group7.ipynb>
2. Trend analysis on relevant data <Metro_Homes.ipynb>
3. Prediction using the Trend Data <Metro_Homes_Forecast.ipynb>
   
# 4. Conclusions
- Single Family Home has the highest share of all residential properties sold in US metro areas. Condo/Co-Op, Townhouse and Multi-family homes are the next highest selling types respectively.
- Housing sales peaked in 2021 and is in gradual downward trend since.
- Average median sales price is in continuous upward trajectory for all property types since the begining of our data in 2012. Townhouse has the highest average median sales price, followed by Multi-family, Single Family and Condo/Co-Op.
- The rate of price change increased rapidly from 2020 to 2022 with some tapering in 2023
- The number of units sold is highest in June, with May, July and August also remaining high.
- Top 5 metro areas based on 2023 analysis of all residential homes sold are:
     1. Houston, TX
     2. Atlanta, GA
     3. Chicago, IL
     4. Phoenix, AZ
     5. Dallas, TX
- The units sold in 5 highest metro areas followed the national trend with sales (units) peaking in 2021 and trending down since.
- Among the top 5 metro areas based on units sold, the following have the highest average median sales price:
     1. Phoenix, AZ
     2. Dallas, TX
     3. Atlanta, GA
     4. Chicago, IL
     5. Houston, TX
- Similar to national trend, the rate of price change increased rapidly from 2020 to 2022 for the top 5 metro areas, with some tapering in 2023
- The forecast for Single Family Homes sold for next 12 months is predicted to go down from 2023 level.
- The home sale pattern will follow the same seasonality observed in last periods.
- Single family homes sales is predicted to peak in May of 2024 with probability of 258,269 units sold. The range could be from low of 232,164 to the high of 284,240.
- The forecast for Single Family Homes average median sale price for next 12 months is predicted to go down from 2023 level.
- The average median sales price fluctuation pattern will follow the same seasonality observed in last periods.
- Average median sales price of Single family homes is predicted to peak in June with probability of $333,095. The range could be from low of $327,884 to the high of $338,549.
