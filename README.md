# Project1_Group7

# Project Team
Anup Pathak, Dharmesh Gautam, Melisa Venegas, Sandeep Kothapalli

# 1. About the Project
Redfin is a real estate brokerage, having direct access to data from local multiple listing services, as well as insight from their real estate agents across the country. This data summarize the monthly housing market for every State, Metro, and Zip code in the US from 2012 to 2023. The project aims to analyze the housing data, understand the trends in data, and present its readers steps the team took to draw insights from the trends. The project also includes forecast for the next 12 month period based on the trend data. 

The purpose of this learning project is to show the most relevant technical aspects of Python libraries and use of Prophet to address the analytical requirements of the project.

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
The raw data was downloaded from the original source into an tabbed separated values for the initial analysis. The original data filesize was significantlly large, making it difficult to perform the analysis, given the limitations of the free tools used for analysis. After a quick review of the data, the initial file was reduced in size by selecting the most relevant features required for the analysis. The new layout was stored as a standard CSV file which served as an input for the rest of the analysis.

### Analytical Approach
1. Undersand the raw data by profiling the data and reviewing the published data dictionary
2. Identify opportunities for analysis and prediction (See below)
3. Prepare data for analysis by reading relevant data using Pandas
4. Idenify trends in data by using Matplotlib libraries 
5. Seek insights from the data
6. Predict likely trend using Google's Colab and 'Prophet'
7. Draw conclusions

### Opportunities for analysis
While the project team found the data rich for analysis, given the time and project constraints, the team focussed their efforts on th following areas of analysis. 
1. National trends  across all metro areas in number of homes sold and home prices by property type across the period
2. Top 5 Metro markets for the recent period, 2023
3. Trends in Top 5 metro markets for homes sold and home prices by property types across period
4. Seasonality in the homes sold across all metros and across the period over a 12 month cycle
5. curve fitting and prediction for the next 12 month period for single family homes across all metro areas

And while we used either top 5 metro areas  or all metro areas for analysis to showcase some of the analytical capabilities in this project, We feel we can extend this approach to analyzing and precition for any region or group of metros, depending on the business need.

### Missed opportunities
Given the time constraints, we could not use the data for expanding our analysis for correlation studies. We also wanted to study the impact of Covid on the housing market, but could not do so at this time. We leave these analyses for a separate endeavor.

we also envisioned that, in order to expand our study of coorelation between important variables, we may need additional data sources, such as demographic, income, or census data, to supplement the real estate market data.

# 3. The Solution
The solution has been uploaded to the Github into the project repo. It can be found here: https://github.com/mvenegas011/Project1_Group7.

It primarily consists of three parts:
1. Ingesting the initial raw data <Project1-group7.ipynb>
2. Trend analysis on relevant data <Metro_Homes.ipynb>
3. Prediction using the Trend Data <Metro_Homes_Forecast.ipynb>
   
# 4. Conclusions
Write your conclusions here.

Text1

Text2
