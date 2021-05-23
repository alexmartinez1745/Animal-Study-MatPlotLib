## Background

Tools used: Python (Matplotlib), Python (Pandas), Jupyter Notebook

Was given access to a complete dataset from a recent animal study. The study has data that includes screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. In this study, 249 mice identified with SCC tumor growth and were treated through a variety of drug regimens The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens over the course of 45 days. 

## Instructions

* Before beginning the analysis, scanned the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID. Then used this data for the remaining analysis. 

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

* Generated pie plots that show the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determined if there were any potential outliers across the four treatment regimens.

* Generated a box and whisker plot of the final tumor volume for the four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.

* Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. (Shown in scatter plot)

* Included observations at the top of notebook from the data.

