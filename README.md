# Customer Call Center Analysis

## Table Of Content

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis Expression](#data-analysis-expression)
- [Results](#results)
- [Recommendation](#recommendation)

### Project Overview

The primary aim of this analysis is to analyze the call center data to identify key trends and insight that can help improve customer service efficiency and Agent Performance. The derived will assist Stakeholders in making data-driven decision to enhance operational efficiency.


### Data Sources
The Primary dataset used for this analysis is the "CallCenterDataset.xlsx" file.

### Tools
- Excel - Data Inspection
- Power Query - Data Cleaning 
- Power BI - EDA and Report Creation
 

 ### Data Cleaning

The following data cleaning process was carried out:

1.  Data Inspection :Data Inspection was carried to identify duplicate values, missing values, checking datatype  
2. Handling Missing Values : Missing values were identified and were filled. 
3. Data Classification: Some Data were classified into categorical format for easy analysis.

### Exploratory Data Analysis

The Exploratory Analysis was done to answer key questions which are :

- What is the Overall Customer Satisfaction Rating?
- What is the Average Speed of Answered Calls?
- What time Duration has the heighest Call?

### Data Analysis Expression

``` DAX
Avg Satisfaction Rating = DIVIDE(AVERAGE(Sheet1[Satisfaction rating]), 5,0)
```



### Results

The Report presents the performance of a call center performance for a given year.

- The report shows January having the highest number of calls.
- The analysis shows a call rating performance of 55%
-  From the analysis shows that between 9am-11am the highest number of calls are recieved.
- The agent performance shows that Jim has the highest call performance. 

### Recommendation
Based on the Analysis, we recommend the following actions:

- Agent with longer talk duration may need better issue resolution strategies in order to boost performance rating.
- A system upgrade can be done for the CRM system in order to channel customers to the best fit agent for their query type.
- Use data from call topics to proactively address frquent issues.
