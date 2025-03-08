# Course-Work
MTCARS Data Analysis Project(Claa work)

This project explores the `mtcars` dataset in R by visualizing and analyzing its variables. Key tools include base R functions and the `ggplot2` library for creating customized visualizations.

Table of Contents
- Introduction
- Dataset Overview
- Installation
- Steps in the Project
- Visualization Example
- Dependencies
- License

Introduction
The purpose of this project is to analyse the `mtcars` dataset and visualize relationships between its variables, focusing particularly on the correlation between horsepower (hp) and weight (wt).

Dataset Overview
The `mtcars` dataset contains information on automobile design and performance extracted from the 1974 Motor Trend US magazine. It includes 32 observations of cars and 11 variables such as `mpg` (miles per gallon), `cyl` (number of cylinders), `hp` (horsepower), and more.

Installation
1. Load the `mtcars` dataset:
   ```R
   data <- mtcars
   data(mtcars)
   head(mtcars)
   summary(mtcars)
install.packages("ggplot2")
library(ggplot2)
Load and Summarize the Dataset:
•	Use head(mtcars) to preview the data.
•	Use summary(mtcars) to summarize the dataset.
Pair Plot:
•	Visualize relationships between all numeric variables using the pairs’ function:
Scatter Plot of Horsepower vs. Weight:
•	Create a scatter plot to analyse the correlation between ‘hp’ and ‘wt’ using the ggplot2 package:
Visualization Example
•	Pair Plot: A comprehensive view of all numeric variables. 
•	Scatter Plot: Visualizes the correlation between horsepower (hp) and weight (wt) with clear labelling and a minimalist theme.
Dependencies
This project depends on the following R packages:
•	ggplot2: For creating customized visualizations.
•	Base R functions such as pairs, head, and summary.
License
This project is open-source and distributed under the MIT License. Feel free to use and adapt it!
