# Climate Change Statistics Application

## Overview

This project is an interactive application that allows users to explore climate change statistics for different countries based on various datasets. The application covers global temperature trends, yearly CO2 emissions, and average temperatures across different dates and countries.

## Project Development

### Data Sources

The project utilizes three main datasets obtained from Kaggle:
- **city_temperature**: Contains data on city-based temperature with columns Country, City, Month, Year, Day, and AverageTemperature.
- **global_temperature**: Provides global temperature data with columns Date, AverageTemperature, and Country.
- **emission**: Focuses on CO2 emissions with columns Country and Yearly CO2 rate.

### Libraries Used

- **Pandas**: Used for data manipulation and analysis, facilitating efficient handling of tabular data.
- **Matplotlib**: A powerful visualization library for creating line graphs, bar graphs, pie charts, etc.
- **IpyWidgets**: Enables the creation of interactive widgets like dropdowns, sliders, and buttons for Jupyter notebooks.
- **IPython**: Used for rendering and displaying widgets to enhance user interaction.

## How to Run the Application

1. Install the required libraries using `pip install -r requirements.txt`.
2. Open the Jupyter notebook (`climate_change_app.ipynb`).
3. Run the notebook cells sequentially to visualize different datasets.

## Acknowledgments

Special thanks to the following sources:
- [Rajkumar's Kaggle Dataset](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities)
- [Sissener's Kaggle Dataset](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- [Favaretto et al., 2020](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7041862/)
- [Kvam, 2017](https://stackoverflow.com/questions/44867290/ipywidgets-jupyter-notebook)
- [Lee, 2023](https://towardsdatascience.com/making-your-data-analytics-come-to-life-using-ipywidgets-cfa9538279f7)
- [Li, 2020](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7303292/)

