# M5_PyBer
## Summary
Module 5 Challenge utilizes pandas functions and matlabplot inorder to look at ride-sharing data. The goals of the challenge include:

1. Technical Analysis Deliverable 1: A DataFrame that summarizes the key metrics for the ride-sharing data by city type.
2. Technical Analysis Deliverable 2: A multiple-line chart, with one line for each city type, that shows the sum of the fares for each week.
3. Delivering Results: A written report of your results, saved in a README.md document on your GitHub repository.

In this notebook, it also includes the module work that was assigned for the entire week. Note that Technical Analysis Deliverable 1 & 2 are at the end of this notebook. All Module work is marked by [MW] in its markdown cell. While the Module Work is present within this notebook, their display function, such as plt.show() has been commented out as a way to condense cell space.

## Procedure

#### Technical Analysis Deliverable 1:
* Generating Variables such as Total Rides/Drivers/Fares and Average Fare per ride/driver into a dataframe

#### Technical Analysis Deliverable 2:
* Renaming Columns, Setting the Index to the Date Column, Copying the Previously Merged pyber_data_df, and creating a new dataframe with only 'City Type', and 'Fare'
* Creating a new DataFrame that only includes 'City Type' and 'Fare', which also includes the sume of fares by the type of city and date
* Using the .loc to sort a new dataframe that is from Jan to April of 2019. Also uses resample() function by week inorder to create weekly time series
* Using the object-oriented interface method, plots the Dataframe previously created

## Findings

The purpose for this assignment was to assist the CEO of PyBer in creating additional analysis on top of the module work that was already completed during the week. Below are the findings from the technical analysis:

#### Technical Analysis 1:
By generating a summary dataframe on the total rides, drivers, fares, average fare per ride and average fare per driver organized by city types, we can see a correlation and differences across different urban cities. Where there is an increase both volue of rides, drivers and fares as the city density (rural, suburban, urban) increases. However, while looking at the average fare per ride and per driver, it can be seen that the average fare decreases as the city density increases.

#### Technical Analysis 2:
The multi-line graph generated for technical analysis 2 provides us a visual confirmation to the findings in technical analysis 1. As city density increases, volume of fares increases as well. Additionally, this graphs maps the fares from 2019-01-01 to 2019-04-31. While there are fluctuations from month to month on volume of fares, the principle holds true that urban cities have more fares volume.

## Challenges
Two of the key insights and challenges derived from this challenge was: 1. Object oriented plotting and 2. importance of pandas.

Object oriented plotting was definitely more difficult in practice, where it was very difficult logically to follow where ax should be declared within the cell. The challenge was solved through trial and error and swithc lines of code.

The importance of pandas as challenge is included here because it highlights that dataframes need to be completely accurate in its data type, such as DateTimeIndex, in order to perform collectly. In other words, this challenge really highlighted the importance of data analyzes in pandas before approach matlabplot. Frequently, I had to refer back to previous cells to check if datatypes are correct inorder to overcome the barriers and issues that arise. 

## Recommendations / Additional Analysis Directions
The fares volume provides a good snapshot for the volume of drivers needed to maintain supply and demand equilibriums for different city types. It will help for forecast entry fare price points if the company decides to enter into a new geographical market.

Additional data analysis can be continued on the path of visualizing/plotting average fare prices per driver across time, and additional analysis can focus on the average fare prices per ride across time. Additionally, since technical analysis 2 only focuses on 4 months, additional analysis can focus on increase time scope inorder to analyze greater macro trends.

## Notes
* Note: Technical Analysis Deliverable 1 & 2 are at the end of this notebook. All Module work is marked by [MW] in its markdown cell. While the Module Work is present within this notebook, their display function, such as plt.show() has been commented out as a way to condense cell space.
