# Ecobici Buenos Aires 2024 - Exploratory Data Analysis

A comprehensive exploratory data analysis (EDA) of Ecobici bike-sharing system usage in Buenos Aires during 2024.

## Dataset Overview

The analysis covers 3,559,284 bike trip records with 17 features capturing trip characteristics, temporal patterns, and geographic data.

## Analysis Sections

**A. Initial Dataset Inspection**
Overview of data structure, data types, and basic statistics.

**B. Duration and Data Cleaning**
Trip duration analysis with data validation and removal of anomalies and outliers.

**C. Temporal Analysis**
Time-based patterns including hourly, daily, and monthly trends in bike usage throughout 2024.

**D. Geospatial Analysis**
Geographic distribution of bike stations, popular routes, and station-to-station movement patterns.

**E. User Analysis**
User behavior patterns, including identification of top users and usage frequency distribution.

## Tools and Libraries

- Python 3.13
- Polars (data processing)
- Matplotlib and Seaborn (visualization)
- NumPy (numerical operations)

## Key Findings

The analysis reveals usage patterns, identifies peak demand periods, highlights the most active users, and provides geographic insights into the Ecobici network across Buenos Aires.

## Requirements

- Python 3.x
- Polars
- Matplotlib
- Seaborn
- NumPy

## Installation

1. Clone the repository and navigate to the project directory.

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Data Source

Data files required:
- `badata_ecobici_recorridos_realizados_2024.csv` (trip records)
- `nuevas-estaciones-bicicletas-publicas.csv` (station information)

Source: https://buenosaires.gob.ar/innovacionytransformaciondigital/datos-abiertos-de-buenos-aires