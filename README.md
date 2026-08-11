# Bradford Weather Visual Analytics

This project uses **visual analytics and Python** to analyse one year of meteorological data collected from the **University of Bradford Weather Station**.

The analysis transforms raw weather sensor data into clear visual insights about seasonal behaviour, extreme weather events, rainfall patterns, and relationships between atmospheric variables.

## Objectives

- Analyse seasonal temperature patterns
- Identify extreme heat and cold events
- Examine rainfall variability and extreme precipitation
- Explore relationships between meteorological variables
- Develop clear and interpretable weather visualisations
- Demonstrate how visual analytics supports weather-related decision-making

## Dataset

The dataset was collected using the **Vantage Pro2 weather monitoring system** and includes variables such as:

- Outdoor temperature
- Rainfall
- Relative humidity
- Dew point
- Atmospheric pressure
- Wind speed

## Data Processing

The project applies several preprocessing steps, including:

- Timestamp standardisation
- Data type conversion
- Missing-value removal
- Time indexing
- Daily aggregation of high-frequency observations

## Analysis

The project includes:

### Temperature Analysis
Daily average temperatures are analysed to identify seasonal trends and extreme temperature events.

### Rainfall Analysis
Rainfall distributions and extreme precipitation events are examined to identify periods of increased hydrological risk.

### Correlation Analysis
Relationships between weather variables are explored using correlation matrices and scatter plots.

### Visual Analytics
Time-series plots, scatter plots, and heatmaps are used to transform complex meteorological data into interpretable insights.

## Key Findings

- Temperature shows a clear seasonal pattern across the year.
- Extreme heat events are concentrated mainly during summer.
- Rainfall is highly variable, with occasional intense precipitation events.
- Temperature and dew point show a strong positive relationship.
- Temperature and relative humidity show a moderate negative relationship.
- Wind speed shows relatively weak relationships with the other analysed variables.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

```text
Raw Weather Data
       ↓
Data Cleaning
       ↓
Timestamp Processing
       ↓
Daily Aggregation
       ↓
Exploratory Analysis
       ↓
Time-Series Analysis
       ↓
Extreme Event Analysis
       ↓
Correlation Analysis
       ↓
Data Visualisation
       ↓
Weather Insights
