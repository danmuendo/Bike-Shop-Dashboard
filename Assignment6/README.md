# Waterway Analysis Project

This repository contains the work for **Assignment 6**, which includes two tasks analyzing water quality data from the Boonsong Lekagul waterways.

---

## Tasks Overview

### Task 01
- **Notebook**: `task_01.ipynb`
- **Description**: This task performs exploratory data analysis (EDA) on the provided dataset (`Boonsong_Lekagul_waterways_readings.csv`). Key insights include identifying trends, anomalies, and potential environmental issues.

### Task 02
- **Notebook**: `task_02.ipynb`
- **Description**: This task implements a dashboard using Dash and Plotly to visualize trends, distributions, and anomalies in the waterway dataset. The dashboard includes:
  - Line charts to analyze trends over time.
  - Box plots to identify outliers.
  - Distribution plots to observe variability.
  - Heatmaps to highlight temporal and spatial patterns.

---

## How to Run

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required Python libraries: `dash`, `dash-bootstrap-components`, `plotly`, `pandas`

Install dependencies:
```bash
pip install dash dash-bootstrap-components plotly pandas
```

## Running the Dashboard
```bash
git clone https://github.com/ruc-data-viz/assignment-6-ndoddi.git
cd assignment-6-ndoddi
```
Open the files in an editor and then run them

Open your browser and go to http://127.0.0.1:8050.

## Dataset

The dataset `Boonsong_Lekagul_waterways_readings.csv` contains water quality data, including:
- Sampling dates and locations.
- Measures such as dissolved oxygen, total coliforms, and other pollutants.


## Visualizations

The dashboard provides the following visualizations:

1. **Line Chart**: Trends for selected measures over time.
2. **Box Plot**: Variability and outliers for different locations.
3. **Distribution Plot**: Histogram of values for selected measures.
4. **Heatmap**: Spatial and temporal representation of data trends.
5. **Comparison Plot**: Analyze trends for multiple measures.
