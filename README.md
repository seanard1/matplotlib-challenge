# matplotlib-challenge
Pymaceuticals, Inc. study of cancer treatments in mice

# Instructions/Premise
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

# Modules
matplotlib.pyplot
pandas
scipy.stats

# Summary
This Jupyter Notebook collects to sets of data related to the cancer-drug testing of mice. After combining the datasets and cleaning duplicates, an analysis of the drug regimens is performed, including summary statistics and overview charts. 
After that, we take a deeper look at four of the drug regimens to test for outliers in the data and then perform additional analysis on one of the more promising drugs, including confirming the expected correlation between mouse size and tumor volume. 
There is also a function to chart the tumor volume over time for any mouse that the user wishes.
Ultimately, we check the correlation coefficient for all the drugs when it comes to tumor volume over time to confirm the two regimens that show a reduction in tumor size.
This result is summarized in the analysis section at the top of the Jupyter Notebook.

# Notes

Please see the comments in the pie chart sections of the Jupyter Notebooks. My output is different than the suggested code we were given, but I believe for good reason. I believe the suggested code was not answering the question as it was stated. 

# Citations

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.duplicated.html
After attempting a more complicated solution to find the duplicate mouse data, this resource helped me simplify the code.

https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.round.html 
I found this resource to round of the numbers that were being returned for correlation and regression with too many decimal places to be aesthetically pleasing in a report.

https://python-charts.com/distribution/box-plot-matplotlib/
This resource showed me how to highlight the outliers in the box plots.