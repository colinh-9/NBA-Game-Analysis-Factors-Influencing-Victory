# NBA-Game-Analysis-Factors-Influencing-Victory

## Overview
This project investigates key factors contributing to winning in the NBA using data from the nba.sqlite database. Various statistical techniques, including correlation analysis and visualization, are employed to understand the impact of different performance metrics on game outcomes.

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
3. Open and run the `NBA_Analysis.Rmd` file in RStudio or another R environment.

