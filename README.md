# Principal Component Analysis (PCA)
A Python data analysis project applying Principal Component Analysis (PCA) to global governance, economic, environmental, demographic, and income-level indicators.

## Overview
This project uses 2022 World Bank data to explore relationships among indicators across countries and apply Principal Component Analysis to reduce dimensionality and identify patterns within the data.
The analysis includes data preparation, visualization, standardization, PCA, component interpretation, and cos² analysis to evaluate how well observations and variables are represented by the principal components.

## Variables
The analysis includes:
- Control of Corruption
- Rule of Law
- Inflation
- Trade as % of GDP
- Unemployment Rate
- GHG Emissions per Capita
- Urban Population %
- Income-level classifications
Income classifications were created from GNI per capita and represented using dummy variables for PCA.

## Analysis
The project includes:
- Data cleaning and preparation
- Creation of income-level classifications
- Dummy encoding of income categories
- Standardization of PCA variables
- Exploratory data visualization
- Principal Component Analysis
- Explained variance analysis
- PCA scores and loadings
- Variable correlations with principal components
- Row and variable cos² analysis
- Observation filtering using cos²
- Interpretation of principal components

## Visualizations
Several visualizations are used to interpret the data and PCA results, including:
- Income-group boxplots
- Governance indicator scatterplot with regression line
- Explained variance plot
- PCA observation scatterplot
- Correlation circle
- Loadings heatmap
- PCA biplot
- Cos² distribution
- Variable cos² plot
- Filtered cos² biplot
The filtered biplot focuses on observations that are more strongly represented by the first two principal components.

## Technologies
- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- Prince

## Skills Demonstrated
- Data cleaning and preprocessing
- Feature engineering
- Data standardization
- Dimensionality reduction
- Principal Component Analysis
- Exploratory data analysis
- Statistical visualization
- PCA loadings and correlations
- Cos² interpretation
- Data-driven interpretation

## Data Source
World Bank indicators for 2022 were used for the analysis, including economic, governance, environmental, and demographic measures.

## Project File
The complete analysis, Python code, visualizations, and observations are available in the Jupyter Notebook included in this repository.

## Author
Mercedes Collins
