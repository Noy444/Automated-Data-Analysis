# Automated-Data-Analysis

This project provides an automated data analysis and visualization tool designed to simplify statistical analysis and plotting. The code is structured into two main steps:

1. **Data Input**: This step allows the user to upload a dataset, select relevant columns, and ensure data is clean and formatted correctly.
2. **Visualization**: After providing the data, users can generate various visualizations (bar charts, line plots, and pie charts) and conduct statistical tests (ANOVA and Post Hoc) to analyze relationships between the variables.

## Features

- Upload an Excel file and select specific columns for analysis.
- Reverse Hebrew characters in the data if necessary.
- Generate various plot types: bar charts, line plots, and pie charts.
- Perform statistical analysis using ANOVA and Post Hoc tests.
- Visualize significant results with highlighted cells and Tukey HSD test results.

## Installation

1. Ensure you have a Python environment set up with the following libraries installed:

    ```bash
    pip install pandas matplotlib statsmodels google-colab
    ```

2. Download the code or clone the repository:

    ```bash
    git clone https://github.com/your-username/automated-data-analysis.git
    ```

3. Open the Python script or Jupyter Notebook where the code is implemented.

## Usage

### Step 1: Data Input

In this step, you will upload your Excel data file, specify relevant columns, and ensure the data is clean and categorized correctly.

1. Run the script or notebook and upload your Excel file when prompted.
2. Enter the sheet name and the column names for the independent and dependent variables.
3. Indicate if any columns are numeric. If not, the tool will reverse any Hebrew characters automatically.

### Step 2: Generate Visualizations

After the data is processed, you can select a plot type and customize how the plots are displayed.

- **Plot Types**: You can choose between bar charts, line plots, and pie charts.
- **Display Options**: You can opt to display all categories in one plot or separate plots.

### Statistical Analysis

The tool performs an ANOVA test on the selected data, highlighting significant results. If significant differences are found, a Post Hoc Tukey HSD test is conducted to compare groups.

## Example

Below is an example of how to use the tool:

1. Upload your Excel file when prompted.
2. Enter the sheet name and column names:

    ```plaintext
    Enter the sheet name: DataSheet
    Enter the independent variable column name: Age
    Enter the dependent variable column name: Income
    ```

3. Choose the plot type:

    ```plaintext
    Which plot would you like to generate? (bar/plot/pie): bar
    ```

4. View the results and proceed to statistical analysis if needed.

## Statistical Analysis

The tool will perform an ANOVA test and provide results in a table format. Significant cells are highlighted, and Post Hoc tests are conducted for significant variables.

Example ANOVA output:

