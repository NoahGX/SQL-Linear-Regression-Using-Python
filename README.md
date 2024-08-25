# SQL using Pandas Library

## Overview
The purpose of this Jupyter Notebook is to provide an introduction to using SQL queries within Python environmentsn using the `pandas` library, as well demonstrating how to perform linear regression analysis on datasets obtained from SQL databases.

## Features
- Execution of SQL queries within a Jupyter notebook.
- Data retrieval from SQL databases.
- Data cleaning and preparation.
- Performing linear regression analysis.
- Visualization of regression results.

## Usage
- Clone the repository or download the `.ipynb` file.
- Open the file in Jupyter Notebook or JupyterLab.
- Ensure all prerequisites are installed.
- Run the cells sequentially to observe the workflow from SQL querying to linear regression analysis.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `matplotlib`, `sqlite3` (for SQL connections), `scikit-learn` (for regression analysis).

## Input
Input data should be stored in an SQLite database. Database diagram and more detailed information about the database can be found [here](https://www.sqlitetutorial.net/sqlite-sample-database/).

## Output
- A DataFrame displaying the queried data.
- Visual plots of data points and the regression line.
- Metrics summarizing the regression analysis.

## Notes
- Ensure the database connection details are updated.
- Ensure the database file is correctly referenced in the notebook for successful connection and querying.
- The linear regression model is basic; for more complex models, consider modifying the regression analysis section.