# Cancer Treatment Study - Data Analysis
>This repository contains Python code for analyzing data from a cancer treatment study. The data consists of two CSV files, mouse_metadata.csv and study_results.csv, >which contain information about the mice used in the study and the results of the study, respectively.
>
The code performs the following tasks:
>
>Merges the mouse_metadata and study_results DataFrames into a single DataFrame.
>Identifies and removes any mouse ID with duplicate time points from the data.
>Generates summary statistics for each drug regimen, including mean, median, variance, standard deviation, and SEM of the tumor volume.
>Creates two bar charts and two pie charts to visualize the data.
>Calculates the final tumor volume of each mouse across four of the most promising treatment regimens, and generates a box plot to show the distribution of the final >tumor volume for all mice in each treatment group.
>Generates a line plot of tumor volume versus time point for a mouse treated with Capomulin, and a scatter plot of tumor volume versus mouse weight for the Capomulin >treatment regimen.
>Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, and plots the linear >regression model on top of the scatter plot.
>
Dependencies
>The following packages are required to run the code:
>
>pandas
>matplotlib
>scipy
>numpy

Usage
>To run the code, simply clone the repository and run the pymaceuticals_starter.ipynb notebook using Jupyter Notebook or a similar environment.

License
>This code is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
>This code was written as part of a project for a data analysis course. Most of the data used in this project was provided by the course instructors.
>Various topics such as usage of agg() i.e. aggregate function, etc. were referenced from https://pandas.pydata.org/.
