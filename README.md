# Data Explorer — Titanic Dataset Analysis

## Objective  
Explore, clean, and analyze the Titanic passenger dataset. Visualize insights using Pandas, NumPy, Matplotlib, and Seaborn.

## Steps  
1. Load the dataset (`titanic.csv`)  
2. Inspect data structure and missing values  
3. Clean data: fill missing values, drop unused columns  
4. Add derived columns (`FamilySize`, `AgeGroup`)  
5. Generate visualizations:  
   - Survival count  
   - Survival by class  
   - Age distribution  
   - Fare distribution by class  
   - Survival rate by age group  
6. Compute summary statistics and group-level analysis  
7. Save cleaned dataset and charts for future use  

## How to Run  
```bash
# install dependencies if not yet installed  
python -m pip install pandas numpy matplotlib seaborn

# start Jupyter Notebook  
python -m notebook

Open data_explorer.ipynb, run all cells, and explore the results.
