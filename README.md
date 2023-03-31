# matplotlib-challenge
 ## Pymaceuticals Inc

* First, import dependencies and read in data from both CSVs

* Merge the data from both CSVs into one DataFrame and attain the number of mice

* Get the duplicate mice ID number that shows up for both mouse ID and timepoint. Attain all data for the duplicate mouse ID. Create a new DataFrame that does not include the duplicated mouse. 

* Check the number of mice in the new DataFrame

 ## Summary Statistics

* Create a table that summarizes important statistics (mean, median, variance, standard deviation, and SEM) of tumor volume first manually and then with a single line of code.

* Import these stastistics into a DataFrame grouped by drug regimen

Bar and Pie Charts

* Create a bar chart for the total number of timepoints for all mice grouped by drug regimen first by using Pandas and then by using PyPlot

* Generate a pie chart showing the distribution of mice by sex first by using Pandas and then PyPlot

 ## Quartiles, Outliers, and Boxplots

* Find the maximum/last recorded timepoint for each mouse in a new DataFrame. Merge this DataFrame with the original DataFrame so the original DataFrame includes the corresponding maximum timepoint for each mouse ID

* Loop through the Capomulin, Ramicane, Infubinol, and Ceftamin drug treatments in a list to calculate the IQR, lower & upper boundaries, and outliers of the tumor volumes. Generate a box plot for this data organized by drug treatment

## Line and Scatter Plots

* Create a line graph of tumor volume versus time point for the mice in the Capomulin treatment group

* Generate a scatter plot of average tumor volume vs. mouse weight for the mice in the Capomulin treatment group

* Finally, calculate the correlation coefficiant and linear regression model for average tumor volume vs. mouse weight for the mice in the Capomulin treatment group


 
