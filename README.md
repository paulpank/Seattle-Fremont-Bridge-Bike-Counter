# Seattle's Fremont Bridge Bike Counter Analysis

## Project Overview

This repository contains an exploratory data analysis (EDA) of over a decade of hourly cyclist data from Seattle's iconic Fremont Bridge. The goal of this project was to uncover and visualize the underlying patterns, trends, and anomalies in the city's bike traffic.

The analysis, conducted in a Jupyter Notebook, uses Python with the Pandas, Matplotlib, and Seaborn libraries.

## Key Questions Explored

This analysis dives into the data to answer several key questions:

1.  **What is the daily and weekly rhythm of bike traffic?**
2.  **How has seasonality and weather impacted ridership over the years?**
3.  **Can we see the impact of the COVID-19 pandemic on commute patterns?**
4.  **Are there unique traffic "signatures" for major holidays like July 4th and New Year's Day?**
5.  **What long-term trends have emerged in recreational (weekend) vs. commuter (weekday) cycling?**

## Visualizations

The notebook includes a gallery of visualizations created to tell the story of the data, including:

*   **Time-series plots** showing daily traffic and rolling averages to highlight seasonal trends.
*   **Bar charts** comparing average traffic across months, years, and days of the week.
*   **Heatmaps** illustrating the busiest times by hour, day, and month.
*   **Comparative line charts** that contrast pre- and post-pandemic commute patterns.


## Data Source

The data used in this analysis is from the City of Seattle's public data portal for the Fremont Bridge Bicycle Counter. The full dataset covers the period from 2012 to present.

## How to Run This Notebook

1.  Clone this repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn jupyterlab
    ```
3.  Launch Jupyter Lab and open the `.ipynb` notebook file.
    ```bash
    jupyter lab
    ```

## Summary of Findings

The analysis reveals strong seasonal and weekly patterns dominated by daily commutes. Interestingly, we can clearly see the impact of major holidays, with late-night spikes corresponding to fireworks displays. The comparison between pre- and post-pandemic periods also suggests a tangible shift in commuting habits, particularly on Fridays.
