## EXPERIMENT4_DATA-WRANGLING-AND-VISUALIZATION

## Introductio
This project focuses on analyzing student performance data to explore how different features (Track, Gender, Hometown) impact average grades. It includes two main tasks: creating filtered DataFrames based on specific criteria and visualizing the impact of different features on average grades. This document provides guidance on how to execute these tasks.

## Prerequisites 
1. Software Used:
  - Jupyter Notebook for coding
  - GitHub for repository sharing
    
2. Python libraries:
  - Pandas 
  - Matplotlib

## Installation and Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Nello-zz/EXPERIMENT4_DATA-WRANGLING-AND-VISUALIZATION
2. Navigate to the project directory: `cd EXPERIMENT4_DATA-WRANGLING-AND-VISUALIZATION`
3. Install the necessary Python packages:
   - If you are using Jupyter Notebook, run the following command in a notebook cell:
     ```python
     !pip install pandas
     !pip install matplotlib
     ```
4. Ensure the `board2.xlsx` file is in the project directory.

5. Load the excel file into a DataFrame using the following code:
   ```python
   import pandas as pd
   
   board_df = pd.DataFrame(pd.read_excel('board2.xlsx'))
   board_df
  
## Problem 1: Creating DataFrames
  Objective: Create two DataFrames with the specified conditions

## Problem 2: Generating Plots for Visualization**
  Objective: Create visualizations to analyze the impact of Track, Gender, and Hometown on average   
  scores.

## Expected Results
**Problem 1:** the output DataFrames Instru and Mindy should reflect the filtered data according to the specified criteria.

**Problem 2:** the visualizations should display how Track, Gender, and Hometown influence average grades, showing rankings and comparisons.

## Troubleshooting
- Ensure the data file board2.xlsx is correctly placed in the project directory and accessible.
- Verify that column names in your code match those in the dataset.
- If plots do not display correctly, check if all required libraries are installed and correctly imported.
     
