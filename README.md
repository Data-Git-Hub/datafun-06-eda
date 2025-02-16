# datafun-06-eda

## Introduction
### This project conducts an Exploratory Data Analysis (EDA) on VA Disability Compensation recipients at the county level across the United States for Fiscal Year (FY) 2023. By leveraging datasets from the Department of Veterans Affairs (VA), the U.S. Census Bureau, and economic indicators, this study aims to:
### - Understand regional disparities in VA Disability Compensation.
### - Compare urban vs. rural disability compensation rates using U.S. Census definitions.
### - Analyze relationships between compensation rates, county populations, gender distribution, and cost of living.
### - Utilize geospatial mapping to identify patterns in disability compensation distribution.

### This repository contains all Jupyter Notebook files, datasets, and required dependencies to reproduce the analysis.

## Getting Started
### - To get started with this project, follow these steps.

## Clone the Repository
### First, download the project by cloning the repository:

git clone https://github.com/Data-Git-Hub/datafun-06-eda.git
cd datafun-06-eda

### Set Up a Virtual Environment (Recommended)
### It is recommended to create a virtual environment to manage dependencies.

# Create a virtual environment
python -m venv .venv

# Activate the virtual environment
# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

### Dependencies

* jupyterlab
* pandas
* matplotlib
* seaborn
* openpyxl
  
### Once inside the virtual environment, install the required dependencies using the requirements.txt file:
pip install -r requirements.txt

### Alternatively, install them manually:
pip install jupyterlab pandas matplotlib seaborn openpyxl

### Installing

### Dataset Requirements
### The datasets required for this analysis are stored in the data/ folder:

### datafun-06-eda/
### │── data/
### │   ├── FY_2023_Disability_Compensation_Recipients_by_County.csv
### │   ├── co-est2023-pop.xlsx
### │── notebooks/
### │   ├── datafun-eda.ipynb
### │── README.md
### │── requirements.txt

## Please note that there are additional files the data folder and docs folders that are for future projects.

### Executing program
### To run the project, follow these steps:

### Start Jupyter Notebook
### Open Jupyter Notebook inside the project directory:
jupyter lab

### Open the Notebook
### - Navigate to the notebooks/ folder.
### - Open datafun-eda.ipynb.

### Run the Notebook Cells
### - Follow the step-by-step execution of the notebook.
### - Each section will load data, clean it, perform analysis, and generate insights.

## Help

### Common Issues and Fixes
### Jupyter Notebook Not Found
### If Jupyter is not installed, run:
pip install jupyterlab

### ModuleNotFoundError for OpenPyXL (Excel Data Handling)
### If you encounter:
## ModuleNotFoundError: No module named 'openpyxl'
### Install it with:
pip install openpyxl

### Environment Issues
### If dependencies are not loading, restart the kernel and rerun:

### - Click Kernel → Restart & Run All in Jupyter Notebook.

## Authors

Contributors names and contact info
@github.com/Data-Git-Hub

## Version History
* 4.0
    * Finalization of this Phase of the Project
    * Final Formatting
* 3.0
    * Data Analytics
* 2.0
    * Data Transformations
* 1.0
    * Cleaning Datasets
* 0.0
    * Initial Setup
