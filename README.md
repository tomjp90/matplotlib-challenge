# Matplotlib Assignment

In this assinment, potential treatments for skin cancer is analysed using data obtained from mice on different treatment options. Tables and graphs using  pandas and matplotlib are created to summarise the study results.

## Technologies Used:
* Python
* Matplotlib
* Pandas
* Scipy.stats
* Numpy
* Sklearn


## Steps

* Check the data for any mouse IDs with duplicate time points and remove any data associated with that mouse ID.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Calculate the quartiles and IQR and quantitatively determine the outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. 

* Plot the linear regression model on top of the previous scatter plot.
