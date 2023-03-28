# Cancer Treatment Study - Data Analysis
>This repository contains a folder named ['Pymaceuticals'] and a ReadMe file. The Pymacueticals folder further contains the Python code (pymaceuticals_starter.ipynb) for analyzing data from a cancer treatment study. The ['Data'] sub-folder consists of two CSV files, Mouse_metadata.csv and Study_results.csv, which contain information about the mice used in the study and the results of the study, respectively.
>
The code performs the following tasks:
>
>1. Merges the mouse_metadata and study_results DataFrames into a single DataFrame.
>
>2. Identifies and removes any mouse ID with duplicate time points from the data.
>
>3. Generates summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.
>
>4. Creates two bar charts and two pie charts to visualize the data.
>
>5. Calculates the final tumor volume of each mouse across four of the most promising treatment regimens, and generates a box plot to show the distribution of the final tumor volume for all mice in each treatment group.
>
>6. Generates a line plot of tumor volume versus time point for a mouse treated with Capomulin, and a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
>
>7. Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, and plots the linear regression model on top of the scatter plot.
>
Dependencies
>The following packages are required to run the code:
>
>1. pandas
>
>2. matplotlib
>
>3. scipy
>
>4. numpy
>
Usage
>To run the code, simply clone the repository and run the pymaceuticals_starter.ipynb notebook using Jupyter Notebook or a similar environment.

Contact
>If you have any questions or feedback about this script, please feel free to contact me at param.birdi@utoronto.ca.

Acknowledgments
>This code was written by Paramdeep Singh Birdi as part of a project for a data analysis course. Most of the data used in this project was provided by the course instructors.
>Various topics such as usage of agg() i.e. aggregate function, etc. were referenced from https://pandas.pydata.org/.
