# NBA-Game-Analysis-Factors-Influencing-Victory

## Overview
This project investigates key factors contributing to winning in the NBA using data from the nba.sqlite database. Various statistical techniques, including correlation analysis, logistical modeling and visualization, are employed to understand the impact of different performance metrics on game outcomes. There are two separate .rmd files and PDF files in this repository: (1) The [`Log_Models_NBA_Analysis.Rmd`](Log_Models_NBA_Analysis.Rmd) and [Logistic Models/Heat Map PDF Report](NBA_Analysis.pdf), which provide context to why I wanted to look into the [`NBA_Analysis.Rmd`](NBA_Analysis.Rmd) and [Correlation Analysis PDF Report](NBA_Analysis.pdf).

## Data
The data used in this analysis is sourced from the nba.sqlite database, containing detailed game statistics over multiple decades. Download the dataset from this link: https://www.kaggle.com/datasets/wyattowalsh/basketball/data

## Key Metrics Analyzed
- Free Throw Percentage (FT%)
- Field Goal Percentage (FG%)
- Three-Point Percentage (3P%)
- Rebounds
- Turnovers

## Analysis
The analysis explores yearly correlations between these metrics and the margin of victory. Key insights include the evolving importance of three-point shooting, the consistent impact of rebounding, and the significance of turnovers.

## Limitations
The analysis is subject to data limitations, including incomplete records for certain years and potential biases in data collection. Changes in game rules over time may also influence the observed trends.

## Conclusion
The findings provide valuable insights for teams and analysts aiming to enhance their competitive strategies. Future research should incorporate more comprehensive datasets and consider additional variables to improve the robustness of the analysis.

## How to Use
1. Clone the repository:
    ```sh
    git clone https://github.com/colinh-9/NBA-Game-Analysis-Factors-Influencing-Victory.git
    cd NBA-Game-Analysis-Factors-Influencing-Victory
    ```
2. Ensure you have the necessary libraries installed:
    ```r
    install.packages(c("DBI", "RSQLite", "ggplot2", "dplyr"))
    ```
3. Open and run the [`Log_Models_NBA_Analysis.Rmd`](Log_Models_NBA_Analysis.Rmd) and/or [`NBA_Analysis.Rmd`](NBA_Analysis.Rmd) file in RStudio or another R environment to reproduce the analysis.
4. You can also view the analysis results directly in the [Logistic Models/Heat Map PDF Report](Log_Models_NBA_Analysis.pdf) and/or [Correlation Analysis PDF Report](NBA_Analysis.pdf) for a detailed summary and visualization of the findings.
