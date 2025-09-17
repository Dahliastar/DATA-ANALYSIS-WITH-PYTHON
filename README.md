# Iris Dataset Analysis

A comprehensive Python script for analyzing the famous Iris flower dataset, including data exploration, visualization, and statistical analysis.

## Overview

This project performs exploratory data analysis on the Iris dataset, which contains measurements of sepal and petal dimensions for three species of iris flowers: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Requirements

Make sure you have the following Python libraries installed:

```bash
pip install pandas matplotlib seaborn numpy
```

## Required Libraries

- `pandas` - Data manipulation and analysis
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `numpy` - Numerical computing

## Dataset

The script expects an `Iris.csv` file in the same directory. The dataset should contain the following columns:
- `Id` - Unique identifier for each sample
- `SepalLengthCm` - Sepal length in centimeters
- `SepalWidthCm` - Sepal width in centimeters
- `PetalLengthCm` - Petal length in centimeters
- `PetalWidthCm` - Petal width in centimeters
- `Species` - Iris species (setosa, versicolor, virginica)

## Features

### Data Exploration
- Display first 15 rows of the dataset
- Check data types for key columns
- Identify the most common iris species
- Basic statistical summary using `describe()`

### Data Cleaning
- Simulate and handle missing values
- Fill numerical missing values with mean
- Fill categorical missing values with 'unknown'
- Verify data integrity after cleaning

### Data Visualization
The script generates four types of visualizations:

1. **Bar Chart** - Correlation between sepal and petal length
2. **Histogram** - Distribution of petal width measurements
3. **Scatter Plot** - Sepal vs. petal length with species differentiation
4. **Pie Chart** - Distribution of iris species in the dataset

### Statistical Analysis
- Calculate mean measurements grouped by species
- Generate insights about species characteristics
- Provide data-driven conclusions

## Usage

1. Ensure you have the required libraries installed
2. Place your `Iris.csv` file in the same directory as the script
3. Run the Python script:

```bash
python iris_analysis.py
```

## Output

The script will display:
- Dataset preview and structure information
- Missing value handling results
- Statistical summaries
- Multiple visualization plots
- Mean measurements by species
- Key findings and conclusions

## Key Findings

Based on the analysis, the script identifies several patterns:
- **Iris-virginica** has the greatest average sepal length
- **Iris-versicolor** has the least average sepal width
- **Iris-virginica** has the greatest average petal length
- **Iris-setosa** has the least average petal width

## Code Structure

The analysis follows these main steps:
1. Data loading and initial exploration
2. Data type verification
3. Missing value simulation and handling
4. Data visualization (4 different plot types)
5. Statistical analysis and grouping
6. Summary of findings

## Note

The script includes intentional missing value simulation for demonstration purposes. In a real-world scenario, you would handle actual missing values in your dataset.

## License

This project is for educational purposes and demonstrates basic data analysis techniques using Python's data science libraries.
