# README

## Project Title: Cholera Dataset Analysis

### Description
This project analyzes a cholera dataset to clean, standardize, and transform the data for further analysis. The project primarily involves standardizing variable names, renaming specific columns, and selecting relevant features from the dataset. The goal is to ensure data consistency and enhance the dataset's usability for statistical analysis and visualization.

### Project Structure
The Jupyter Notebook contains the following sections:

1. **Environment Setup:**
   - Installs necessary packages such as R to support data processing and analysis.

2. **Data Cleaning and Standardization:**
   - Standardizes variable names and stores the cleaned data in an object named `clean_data`.
   - Renames specific columns as follows:
     - **sanitation facility** → **toilet**
     - **cholera vaccination** → **immunization**
     - **region** → **territory**

3. **Data Selection:**
   - Selects key columns from the cleaned dataset, including:
     - The first five variables.
     - Variables 3, 5, and 8.
     - Variables containing the letter "s".

### Prerequisites
To successfully run the notebook, ensure you have the following:
- Python 3.x installed
- Jupyter Notebook environment
- R language support (installed via the notebook)

### Installation
To set up the environment, run the following commands in the notebook:
```bash
!apt-get install -y r-base
!R --version

### Usage
1. Open the Jupyter Notebook.
2. Run the setup cells to install the required packages.
3. Execute the data cleaning and transformation steps.
4. Analyze the cleaned and processed dataset.

### Author
Cosmas Muange
