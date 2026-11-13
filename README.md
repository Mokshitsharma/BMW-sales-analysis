<!-- readme-refresh 2026-11 -->
<div align="center">

# 🚗 BMW Sales Analysis

**Worldwide BMW sales 2010–2024: EDA and a Power BI dashboard**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" /> <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" /> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />

</div>

## ✨ Highlights

- Cleaning and EDA of 2010–2024 sales
- Power BI dashboard (`BMW sales dashboard.pbix`)

<!-- body -->
## Project Overview
This project is a data analysis and visualization application for BMW sales from 2010 to 2024. The core dataset includes model details, sales volume, price, engine specs, and sales classifications across multiple regions. The analysis leverages Python and powerful data visualization libraries to uncover trends, top-selling models, and regional performance for BMW vehicles.[1]

## Features
- **Data Cleaning & Preparation**: Handles missing values and duplicates for robust analytics.[1]
- **Exploratory Data Analysis**: Key metrics calculated (mean, min, max, quartiles) for year, engine size, price, and sales volume.[1]
- **Sales Trend Visualization**: Yearly sales trends plotted using seaborn and matplotlib.
- **Top Models & Regional Analysis**: Identifies the best-selling models and highlights sales by region.[1]
- **Fuel Type Insights**: Reports on hybrid, petrol, electric, and diesel sales.[1]
- **Customizable Dashboards**: Build interactive charts with Matplotlib, Seaborn, and Plotly Express for tailored business insights.[1]

## Requirements
- Python 3.8 or newer
- pandas
- numpy
- seaborn
- matplotlib
- plotly

## Installation

```bash
# Set up environment & dependencies
pip install pandas numpy seaborn matplotlib plotly
```

## Usage

1. Place `BMWSales2010-2024.csv` in your working directory.
2. Run the analysis script using Jupyter Notebook or any Python IDE.
3. Interactive charts and tables will be generated for exploration.[1]

Example code snippet:

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px

df = pd.read_csv('BMWSales2010-2024.csv')
# Proceed with analysis and visualizations
```

## Data Columns

| Column Name         | Description                  |
|---------------------|-----------------------------|
| Model               | BMW car model name           |
| Year                | Model year                   |
| Region              | Sales region (Asia, Europe, etc.) |
| Color               | Car color                    |
| FuelType            | Fuel type (Petrol, Diesel, Hybrid, Electric) |
| Transmission        | Automatic/Manual             |
| EngineSizeL         | Engine size in liters        |
| MileageKM           | Mileage in kilometers        |
| PriceUSD            | Price in USD                 |
| SalesVolume         | Units sold                   |
| SalesClassification | High/Low sales indicator     |

## Author
Mokshit Sharma

---

<div align="center"><sub>Built by <a href="https://github.com/Mokshitsharma">Mokshit Sharma</a> · <a href="https://mokshitsharma27.vercel.app/">Portfolio</a> · <a href="https://www.linkedin.com/in/mokshit-sharma-75b5ab305">LinkedIn</a></sub></div>
