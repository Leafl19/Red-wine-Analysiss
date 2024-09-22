# Red Wine Quality Analysis

## Overview
This project provides an in-depth analysis of factors influencing red wine quality, using **SQL** for data cleaning and preparation, **R** for correlation analysis, and **Tableau** for interactive visualizations. The analysis identifies key relationships between chemical properties such as volatile acidity, alcohol content, and wine quality ratings, and provides actionable insights for improving wine production.

## Project Structure
The repository is organized as follows:
- **SQL**: Contains SQL scripts for data cleaning and summary analysis.
- **R_Scripts**: Contains R code for calculating the correlation matrix and exporting the results for visualization.
- **Data**: The dataset used for analysis 
- **Tableau_Workbook**: Tableau visuals 


## Key Findings
- **Volatile Acidity** has a negative correlation with wine quality. Higher volatile acidity levels tend to result in lower-quality wines.
- **Alcohol Content** shows a positive correlation with wine quality. Wines with higher alcohol content generally receive higher quality ratings.
- **Mid-range quality ratings** dominate the dataset, providing an opportunity to improve mid-tier wines through targeted adjustments in volatile acidity and alcohol content.

## Analysis Code

### SQL Code:
- [SQL Code for Data Cleaning and Summary Analysis](SQL/red_wine_analysis.sql)
  
The SQL code cleans and prepares the dataset, converts key variables to appropriate types, and calculates summary statistics such as averages for volatile acidity, alcohol content, and other properties.

### R Code:
- [R Code for Correlation Analysis and Export](R_Scripts/red_wine_correlation_analysis.R)

The R script calculates the correlation matrix between chemical properties and wine quality, visualizes the relationships using `corrplot`, and exports the results for further use in **Tableau**.

## Visualizations
The following visualizations were created to highlight key trends in the data:

1. **Correlation Heatmap**:
   - [Correlation Heatmap](https://public.tableau.com/app/profile/leaf.lewis1752/viz/RedWineDashboard-2/Sheet1?publish=yes)

![Screenshot 2024-09-22 at 11 41 02 AM](https://github.com/user-attachments/assets/8430f29a-a264-4e5a-983e-af7a8ec859e2)

- **Insight**: Alcohol content has a positive correlation with wine quality, while volatile acidity has a negative impact.

3. **Volatile Acidity vs. Wine Quality (Scatter Plot)**:
   - [Volatile Acidity vs. Quality](https://public.tableau.com/app/profile/leaf.lewis1752/viz/RedWineDashboard-3/Sheet3?publish=yes)
     
![Screenshot 2024-09-22 at 11 41 55 AM](https://github.com/user-attachments/assets/63fa6e26-b2a0-4bb8-9e3e-6d46a27421b9)

-  **Insight**: Higher volatile acidity tends to result in lower wine quality ratings.

4. **Average Alcohol Content vs. Wine Quality (Bar Chart)**:
   - [Average Alcohol Content vs. Quality](https://public.tableau.com/app/profile/leaf.lewis1752/viz/RedWineDashboard/Sheet4?publish=yes)
     ![Screenshot 2024-09-22 at 11 44 00 AM](https://github.com/user-attachments/assets/68efc3b4-e03a-4d26-a7ac-881ed87deb1c)

- **Insight**: Higher alcohol content is associated with higher-quality wines.

## Tableau Dashboard
For a fully interactive exploration of the red wine dataset, the **Tableau dashboard** is available for viewing . The workbook includes visuals for correlation heatmaps, scatter plots, and bar charts to help explore the relationships between wine quality and various chemical properties.

- [View Dashboard](https://public.tableau.com/app/profile/leaf.lewis1752/viz/RedWineDashboard-5/Dashboard1?publish=yes)

## Dataset
- **Red Wine Quality Dataset**: [Download Dataset](Data/red_wine_data.csv)


## Recommendations
Based on the analysis, the following recommendations can be made for wineries looking to improve red wine quality:
1. **Control Volatile Acidity**: Reducing volatile acidity during the fermentation process will help produce smoother, higher-quality wines.
2. **Optimize Alcohol Levels**: Higher alcohol content generally leads to higher quality ratings. Wineries may benefit from adjusting alcohol levels to improve wine richness and body.
3. **Focus on Mid-Quality Wines**: A significant portion of wines fall within mid-quality ratings (5-6). By making targeted improvements to these wines, wineries can push more wines into higher-quality brackets.

