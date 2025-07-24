# NavigationAnalysis

## Analysis of Human Navigation Strategies in a Traveling Salesman Environment
This repository contains the Jupyter Notebook and data analysis for my graduate research on human cognitive ability. The project investigates how individuals utilize spatial and temporal memory to develop efficient navigation strategies in a simulated Traveling Salesman Problem (TSP) environment.

The analysis focuses on processing and visualizing trajectory data collected from over 50 participants to uncover patterns and correlations in their problem-solving approaches.

## Research Questions
This analysis aims to answer several key questions:

How does a participant's navigation efficiency improve over 8 trials?

What is the correlation between a participant's cognitive mapping skills and their navigation ability?

Can we identify distinct navigation strategies by visualizing user trajectory data (e.g. is it closer to Nearest Neighbors or Optimal Solution)?

As particpants complete each trial, do their solutions converge, and it is optimal?

## Methodology
The entire analysis is contained within the Online_Exploration_Trajectories.ipynb.ipynb Jupyter Notebook and follows these steps:

Data Cleaning & Preprocessing: The raw experimental data was loaded using Python. I extensively used the Pandas library for data cleaning by removing redundant datapoints and extracted incomplete experimental data.

Feature Engineering: New metrics were engineered to quantify navigation efficiency, such as total path length, Frechet distance, and deviation from optimality. 

Statistical Analysis: The SciPy library was used to perform statistical tests, allowing me to identify significant correlations between different variables (e.g., a participant's spatial ability and their final path length).

Data Visualization: A core component of this analysis was visualization. I used Matplotlib to create a wide variety of plots to explore the data and communicate findings, including:

- 2D trajectory maps to visualize the exact paths participants took.

- Histograms and box plots to show the distribution of path lengths.

- Scatter plots to explore relationships between navigation efficiency and cognitive mapping ability.

## Key Findings
The analysis revealed participants were able to improve their navigation ability across the 8 trials. However, it is unclear if their strategies resembled Nearest Neighbors or Optimal Solutions. 

## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Matplotlib
- SciPy
