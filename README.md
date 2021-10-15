# Cancer Treatment Analysis - The Power of Plots

## Summary

Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. We have been tasked to generate all of the tables and figures needed for the technical report of the study.

## Instructions

Your tasks are to do the following:

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
![Summary Statistics Table](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/summarystats.png)

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

  * **NOTE:** These plots should look identical.
![Bar Chart](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/drugtreatmentsbarchart.png)

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

  * **NOTE:** These plots should look identical.
![Pie Chart](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/malefemalemicepiechart.png)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
![Outile and Outliers Code](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/quartileoutlierscalculations.png)

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
![Box Plot](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/boxplotcombined.png)
* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
![Linear Regression Model](https://github.com/kreetigulati/cancer-treatment-matplotlib/blob/main/images/capomulintumorweight.png)
