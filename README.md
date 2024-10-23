# Employee Survey Analysis

This project analyzes employee satisfaction across different departments using a dataset that includes metrics such as job satisfaction scores, department information, and other relevant employee data. The notebook applies statistical techniques and visualizations to uncover trends and insights into job satisfaction levels.

## Project Overview

The main objectives of this analysis include:
- **Data Exploration**: Visualizing and summarizing key trends in employee satisfaction.
- **Hypothesis Testing**: Performing statistical tests (such as t-tests) to determine if there are significant differences in job satisfaction between departments.
- **Visualization**: Using various types of charts to present the data and insights in an intuitive way.

## Key Features
- **Data Cleaning**: The dataset is cleaned and processed to handle missing or inconsistent data entries.
- **Statistical Analysis**: 
  - A t-test and then Mann-Whitney U test is performed to compare job satisfaction scores between the IT and HR departments.
  - Exploratory Data Analysis (EDA) is conducted to provide initial insights into the dataset.
- **Visualizations**: 
  - The notebook includes visualizations such as bar plots and histograms to illustrate the distribution of satisfaction scores across departments.
  
## Dataset
The dataset contains employee information and survey ratings on different metrics.

## Requirements
To run this project, you will need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `scipy`
  
You can install them using:
```bash
pip install pandas numpy matplotlib scipy
```

## Running the Notebook
1. Clone this repository.
2. Install the required dependencies.
3. Open the notebook (`Employee_satisfaction.ipynb`) and run the cells step by step.

## Statistical Test Summary
A t-test was conducted to determine if there is a statistically significant difference in job satisfaction between the IT and HR departments. However, the test resulted in a **NaN** (not a number) output, potentially due to identical or insufficient data in the groups.

## Results and Insights
- Initial exploratory analysis reveals differences in job satisfaction scores between departments.
- Further statistical analysis is needed to confirm these findings.

## Limitations
- More data or a deeper analysis is required to draw more reliable conclusions.
