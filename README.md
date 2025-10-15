# BMW Sales Data Analysis (2010-2024)

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
Your Name

## License
This project is released under the MIT License.
