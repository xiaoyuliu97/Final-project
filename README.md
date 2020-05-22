# Final-project

# Fama-French Five Factor based Stock Selection Strategy

# Liu Xiaoyu 

## Data

### Availability 

The data are publicly available for download via the online data portal at <http://www.gtarsc.com/#/index>. Registration is required.

### Description 

Our datasets are downloaded from [CSMAR][http://www.gtarsc.com/#/index]. The first dataset, named Fivefac, comes from stocks with different market types. Fivefac consists of 20961 samples and 12 variables, including trading date, portfolios and 10 factors. The second dataset, named SSE50, covers different stocks and their closing price. Fivefac consists of 52722 rows and 3 columns, including trading date and closing price. 

## Code

### Abstract

All data processing and analysis for this report were done in R. The corresponding code EDA is provided to take exploratory data analysis on the raw data; the other code backtest is presented to implement our stock strategy and plot the backtest chart.

### Optional Information

R version 3.6.3 (2020-02-29) -- "Holding the Windsock"
Copyright (C) 2020 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin15.6.0 (64-bit) were used in the project. And The necessary R libraries for the code used for data processing and analysis are:

- quantmod, version 0.4-16 (https://cloud.r-project.org/web/packages/quantmod/index.html)
- ggplot2, version 3.3.0 (https://cloud.r-project.org/web/packages/ggplot2/index.html)
- reshape2, version 1.4.3 (https://cloud.r-project.org/web/packages/reshape2/index.html)
- farver, version 2.0.3 (https://cloud.r-project.org/web/packages/farver/index.html)
- dplyr, version 0.8.5 (https://cloud.r-project.org/web/packages/dplyr/index.html)
Computer information:
CPU: 2.4 GHz Intel Core i5, 8 GB 2133 MHz LPDDR3. 


## Instructions for Use

### Reproducibility

All data preparation and analyses are reproduced, as well as all Figures in the report.

All workflow information is contained in the Reproduce.R script. The general steps are:

1. Exploratory Data Analysis
2. Fama-French Five Factor based Stock Selection

Then all the pictures in my slides and report are reproduced.
Run EDA.R and backtest.R. Then all the pictures in my slides and report are reproduced.
