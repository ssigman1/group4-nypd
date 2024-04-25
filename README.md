# NYPD Corruption: Ignored 311 Complaint
## Description
Our project analyzes ignored 311 complaints about driver misconduct, which we defined as 311 complaints closed in less than 5 minutes from their creation. The data comes from the city of New York, specifically their 311 requests and police precint data. The data is from 2010 to Present and is updated daily. We filtered the data to exclusively show 311 requests related to driver misconduct.
## Execution
A successful analysis was completed by filtering the data set for only 311 complaints about driver misconduct and creating another filter using existing columns in the dataframe to pull all 311 complaints closed in under 5 minutes. In addition, the analysis joins together a 311 complaint dataframe and a police district data frame to determine, which police destricts reported to the complaints. The code also contains a dataframe that filters the complaints by year and shares the total number of complaints in a year as well as the average number of complaints. Through the code, you are able to analyze the duration of the 311 complaints before they were closed, the overall complaint data for a given year, the different types of driver misconduct complaints that occurred, and the police districts involved in the process of the complaint.
## DataWrapper Charts
DataWrapper Line Chart: https://datawrapper.dwcdn.net/f8eCP/1/ 
DataWrapper Bar Chart: https://datawrapper.dwcdn.net/x5D2f/1/
