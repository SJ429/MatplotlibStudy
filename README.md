
# Matplotlib - The Power of Plots

What good is data without a good plot to tell the story?

The project analyzed the performance of Capomulin versus the other treatment regimens.

Python Matplotlib was used to manipulate and visualize the data and findings. 

The analysis used a complete data from two datasets in CSV format. Data set one was Mouse_metadata.csv and a Study_results.csv.
Both datasets were imported, merged,cleaned and the aggregate data diplayed in to Python Pandas dataframes and visualized in Matplotlib. 


##Observations and Insights

1. Ramicane and Capomulin are the two drug regimens that appear to be the two most effective treatment with Standard of Error mean (SEM) at 0.320955 and 0.329346, respectively. However, Capomulin with SEM of 0.329346 was the drug regimen most tested of the ten drug regimens tested in the study although Ramicane has the lowest SEM at 0.320955.

2. Capomulin showed to have a high positive correlation between the mouse weight and average tumor volume with a correlation coefficient of 0.84 and a R-squared of about 0.7089
Of the 248 unique mouse ids in the study, male mice were 125 at 50.4% and the female mice at 123 represents 49.6%. Thus, there was no significant gender bias in the number of mice included in the study

