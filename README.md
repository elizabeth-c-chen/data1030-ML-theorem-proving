# Applying Machine Learning to Automated Theorem Proving Data

## Overview
The work in this repository comprises a semester-long project in the course DATA 1030: Hands-on Data Science at Brown University, a core first-semester course in the Data Science Master’s program. I worked with the Automated Theorem Proving Dataset from the UCI Machine Learning Repository throughout the semester and applied the techniques learned in class throughout the semester, culminating in the final report which can be found in the `report/` directory.

The work in this project was influenced and inspired by the dissertation by Dr. James P. Bridge at University of Cambridge.  The link to the dataset on the UCI Machine Learning Repository website can be found [here](https://archive.ics.uci.edu/ml/datasets/First-order+theorem+proving). The dataset was generated by Dr. Bridge’s work, and in his paper, suggestions for further work included studying alternative class labeling.
I decided to build on Dr. Bridge’s idea by converting the time columns used to generate the target variable into a multi-label indicator target variable, which allowed multiple heuristics to tie for the fastest time. 

The Jupyter notebooks found in the `src/` directory explore creating the target variable, exploratory data analysis, and the experimentation with various machine learning algorithms on the dataset. Saved models for three of the algorithms can be found in the `results/` directory, however, the file for random forest was too large to save in full, so only the best random forest model from my results is included.

## Running my code
To view any of my notebooks, you may install the conda environment used to generate all code in those files. Please run `conda env create -n ml_atp -f ml_atp.yml` from the main project directory. 
