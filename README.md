# Customer Conversion Funnel Analysis

## Overview

This project focuses on analyzing the customer journey through a conversion funnel, from initial website visit to game participation. By tracking this journey, the project aims to understand where potential customers are lost and how many complete the targeted actions. The insights gained can be valuable for optimizing various stages of the funnel and improving overall customer conversion rates.

## Steps

### Database Connection

The first step involves connecting to a PostgreSQL database that stores the relevant customer data. The database contains information about website visits, account creations, applications, and game participation.

### Data Collection

Data is collected through SQL queries that aggregate the data by months and weeks. The queries pull information about the number of unique clients, accounts, applications, and game participation. The dataset is built to include the conversion rate data required for the analysis.

### Conversion Calculation and Visualization

In this step, conversion rates are calculated at each stage of the funnel. These stages are: visiting the website, creating an account, applying for a game, and participating in a game. The data is visualized through interactive plots.

- **Overall Conversion Funnel** - This plot provides a snapshot of the funnel across the entire period, showing how many customers pass through each stage.
- **Monthly Conversion Trends** - This chart reflects the conversion rate trends on a month-to-month basis, revealing patterns or seasonality.
- **Weekly Conversion Trends** - Similar to the monthly trends, but with a finer granularity, this plot helps to identify weekly variations in the conversion rates.

### Analysis and Conclusions

Finally, the visualizations are analyzed to understand customer behavior. For instance, you can identify stages where a significant number of potential customers are lost. Understanding seasonal trends is vital, as certain times of the year may have lower conversion rates. Insights gained from this analysis can help in focusing efforts on the critical aspects of the funnel, and devising strategies for improvement.

## Requirements

- Python
- pandas
- SQLAlchemy
- plotly

## Usage

To utilize the project, you need to execute the script after setting up a connection to your PostgreSQL database. Analyzing the output plots will offer insights into customer behavior and conversion rates.

## Conclusion

Understanding the customer journey through the conversion funnel is critical for any business seeking to optimize customer engagement and conversion. This project provides the tools and analyses necessary for making data-driven decisions that can improve overall customer experience and contribute to business growth.
