# Pymaceuticals
Analysis of pharmaceutical Data using Matplotlib

## Project Description

The goal of the project is to compare the performance of the drug, Capomulin, versus the other treatment regimens. `Python`, `Matplotlib` library, `Pandas` library, and `scipy` library were used in the project. The Mapbox-API was also used to load the base maps. The project was divided into two steps with different levels of complexity.

249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured.

## Observations and Insights
- The gender of the mice is very uniform and almost identical along with the amount of mice per drug regimen is similar.

- The scatter plot demonstrates for Capomulin that the mouse weight and tumor volume possitively correlated and the tumor volume was larger for larger mice.
- The line plot demonstrates that Capomulin decreases the tumor volume over time.
- Capomulin is as effective as the most effective drug at reducing tumors as shown in the boxplot and summary statistics table where the tumor volume mean and median are almost as low as the lowest median and mean, Ramicane.



Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.


Use the cleaned data for the remaining steps.


Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.


Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.


NOTE: These plots should look identical.



Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.


NOTE: These plots should look identical.



Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.


Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.


Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.


Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.


Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.


Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.


Here are some final considerations:


You must use proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, x-axis and y-axis limits, etc.


See the starter workbook for help on what modules to import and expected format of the notebook.
