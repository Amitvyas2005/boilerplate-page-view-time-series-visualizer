# Page View Time Series Visualizer

## Project Objective

This project analyzes and visualizes time series data of daily page views on the freeCodeCamp forum from May 9, 2016 to December 3, 2019. The visualizations help identify patterns, trends, and seasonal variations in forum traffic over the period.

## Overview

The Page View Time Series Visualizer is a data analysis project that creates multiple visualizations to understand visitor patterns on the freeCodeCamp forum:

1. **Line Plot**: Shows daily page views over the entire period (5/2016-12/2019)
2. **Bar Plot**: Displays monthly average page views grouped by year
3. **Box Plots**: Illustrates year-wise and month-wise distribution patterns

## Tools & Libraries Used

- **Python 3.x**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Creating publication-quality visualizations
- **Seaborn**: Statistical data visualization
- **NumPy**: Numerical computing

## Key Tasks Performed

1. **Data Loading**: Import CSV data with proper date parsing and indexing
2. **Data Cleaning**: Remove outliers (top and bottom 2.5% of page views)
3. **Time Series Visualization**: Create line plot for daily trends
4. **Aggregation & Comparison**: Generate bar plot for monthly averages by year
5. **Distribution Analysis**: Use box plots to show trend and seasonality patterns

## Dataset

- **Source**: freeCodeCamp (provided by freeCodeCamp curriculum)
- **File**: `fcc-forum-pageviews.csv`
- **Time Range**: May 9, 2016 - December 3, 2019
- **Original Records**: 1325 days
- **Cleaned Records**: 1238 days (after removing 2.5% outliers on both ends)

## Functions

### `draw_line_plot()`
- Creates a line chart of daily page views
- Shows overall trend across the entire period
- Title: "Daily freeCodeCamp Forum Page Views 5/2016-12/2019"
- Axes: Date (x-axis), Page Views (y-axis)

### `draw_bar_plot()`
- Generates a bar chart of monthly average page views
- Groups data by year and month
- Shows 12 bars for each year (4 years * 12 months = 48 bars)
- Legend displays month names

### `draw_box_plot()`
- Creates two side-by-side box plots
- Left plot: Year-wise distribution (Trend analysis)
- Right plot: Month-wise distribution (Seasonality analysis)
- Shows data spread and outliers for each year and month

## Installation & Usage

```bash
pip install -r requirements.txt
python main.py
python -m unittest test_module.py
```

## Project Link

https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer
