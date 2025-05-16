# COVID-19 Global Data Tracker Project

This project analyzes global COVID-19 trends, focusing on:
- Time trends of cases, deaths, and vaccinations
- Comparisons across countries and regions
- Population density correlation with infection rates
- Relationship between vaccination rates and mortality
- Impact of government responses on case numbers

## Setup Instructions

### 1. Install Required Extensions in VS Code
- Install the "Jupyter" extension in VS Code
- Install the "Python" extension in VS Code

### 2. Install Dependencies
```
pip install -r requirements.txt
```

### 3. Running the Notebook in VS Code
1. Open VS Code
2. Open the `covid19_global_analysis.ipynb` file
3. Click on the "Run All" button at the top of the notebook, or run cells individually by clicking the play button next to each cell
4. If prompted, select a Python kernel to use (make sure it has all the required packages installed)

### 4. Troubleshooting
- If you see "Kernel not found" error, make sure you have Python installed and selected the correct kernel
- If you encounter package import errors, verify that all packages in requirements.txt are installed
- For visualization issues, make sure matplotlib and plotly are properly installed

## Data Source
The analysis uses the Our World in Data COVID-19 dataset, which is automatically downloaded when running the notebook.

## Analysis Sections
1. Data Collection and Setup
2. Data Loading and Exploration
3. Data Cleaning and Preparation
4. Time Trends Analysis
5. Population Density and Infection Rate Analysis
6. Vaccination Impact Analysis
7. Government Response Analysis
8. Geospatial Analysis
9. Key Insights and Conclusions