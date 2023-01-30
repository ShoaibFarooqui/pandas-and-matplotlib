# pandas-and-matplotlib

A demonstration of data visualization with pandas and matplotlib

Assignment description:

# Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

# Instructions
This assignment is broken down into the following tasks:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis

# Requirements

## Prepare the Data (20 points)
The datasets are merged into a single DataFrame. (6 points)
The number of mice are shown from the merged DataFrame. (2 points)
Each duplicate mice is found based on the Mouse ID and Timepoint. (6 points)
A clean DataFrame is created with the dropped duplicate mice. (4 points)
The number of mice are shown from the clean DataFrame. (2 points)

## Generate Summary Statistics (15 points)
The mean of the tumor volume for each regimen is calculated using groupby. (2 points)
The media of the tumor volume for each regimen is calculated using groupby. (2 points)
The variance of the tumor volume for each regimen is calculated using groupby. (2 points)
The standard deviation of the tumor volume for each regimen is calculated using groupby. (2 points)
The SEM of the tumor volume for each regimen is calculated using groupby. (2 points)
A new DataFrame is created with using the summary statistics. (5 points)

## Create Bar Charts and Pie Charts (15 points)
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated. (4.5 points)
A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated. (4.5 points)
A pie plot showing the distribution of female versus male mice using Pandas is generated. (3 points)
A pie plot showing the distribution of female versus male mice using pyplot is generated. (3 points)

## Calculate Quartiles, Find Outliers, and Create a Box Plot (30 points)
A DatFrame that has the last timepoint for each mouse ID is created using groupby. (5 points)
The index of the DataFrame is reset. (2 points)
Retrieve the maximum timepoint for each mouse. (2 points)
The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list. (3 points)
An empty list is created to fill with tumor volume data. (3 points)
A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group (10 points)
A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. (5 points)

## Create a Line Plot and a Scatter Plot (10 points)
A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin. (5 points)
A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen. (5 points)

## Calculate Correlation and Regression (10 points)
The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen. (10 points)