# Final Project – STAT 363

This repository contains the final project for my STAT 363 course, completed in R using Quarto. This study examines how exercise habits, heart rate, and calorie expenditure vary across workout types and genders. This research identifies key trends in fitness routines by analyzing workout duration, heart rate, and calorie burn.

## Project Files

- **`Final_Project_STAT363.qmd`** – Main Quarto file containing all R code, analysis, and visualizations.
- **`fitness_data.Rdata`** – Dataset used in the project.

## Project Overview

In this project, I:
- Loaded and explored a real-world fitness dataset.
- Cleaned and transformed the data for analysis.
- Performed statistical tests and created visualizations.
- Interpreted the results and shared conclusions.

## How to Run

1. Clone or download this repository.
2. Open the `.qmd` file in RStudio (make sure you have the **Quarto** and **tidyverse** packages installed).
3. Load the data file by running the code chunk that loads `fitness_data.Rdata`.
4. Render the `.qmd` file to see the final report (as HTML, PDF, or Word).

```r
load("fitness_data.Rdata")
