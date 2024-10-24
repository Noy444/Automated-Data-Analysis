# Automated-Data-Analysis

This project provides an automated data analysis and visualization tool designed to simplify statistical analysis and plotting. The code is structured into two main steps:

1. **Data Input**: This step allows the user to upload a dataset, select relevant columns, and ensure data is clean and formatted correctly.
2. **Visualization**: After providing the data, users can generate various visualizations (bar charts, line plots, and pie charts) and conduct statistical tests (ANOVA and Post Hoc) to analyze correlations between the variables.

## Features

- Upload an Excel file and select specific columns for analysis.
- Generate various plot types: bar charts, line plots, and pie charts.
- Perform statistical analysis using ANOVA and Post Hoc tests.

## Usage

### Step 1: Data Input

In this step, you will upload your Excel data file, specify relevant columns, and ensure the data is clean and categorized correctly.

1. Run the script or notebook and upload your Excel file when prompted.
2. Enter the sheet name and the column names for the independent and dependent variables.
3. Indicate if any columns are numeric. If not, the tool will treat them as categorical. 

### Step 2: Generate Visualizations

After the data is processed, you can select a plot type and customize how the plots are displayed.

- **Plot Types**: You can choose between bar charts, line plots, and pie charts.
- **Display Options**: You can opt to display all categories in one plot or separate plots.

### Statistical Analysis

The tool performs an ANOVA test on the selected data and highlighting significant results. If significant differences are found, a Post Hoc Tukey HSD test is conducted to compare groups.

