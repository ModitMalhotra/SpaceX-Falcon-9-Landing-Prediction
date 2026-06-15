# SpaceX-Falcon-9-Landing-Prediction
End-to-end data science project to predict whether a SpaceX Falcon 9 first-stage booster will successfully land, helping estimate launch costs through historical launch analysis.

## Project Overview

This project combines data collection, exploratory analysis, visualization, and machine learning to predict Falcon 9 booster landing outcomes.

Data was collected from:
- SpaceX REST API
- Wikipedia web scraping

The final objective is to build a predictive model and an interactive dashboard to analyze launch success patterns.

## Features

- Data collection using SpaceX API
- Web scraping with BeautifulSoup
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- SQL-based querying
- Interactive dashboard using Plotly Dash
- Geospatial visualization using Folium
- Machine learning prediction model

## Dataset Sources

### SpaceX API
https://api.spacexdata.com/

### Wikipedia
https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

## Tech Stack

- Python
- Pandas
- NumPy
- SQL (SQLite)
- BeautifulSoup
- Scikit-learn
- Plotly Dash
- Folium
- Matplotlib
- Seaborn

## Repository Contents

### notebooks
Contains all Jupyter notebooks for:
- Data collection (API & Web Scraping)
- Data wrangling
- Exploratory Data Analysis
- Visualization
- Machine Learning prediction

### dashboard
Contains the interactive Plotly Dash application.

### datasets
Contains cleaned and processed datasets used throughout the project.

### maps
Contains Folium-generated interactive maps.

### project files
- `requirements.txt` → project dependencies
- `.gitignore` → ignored files
- `README.md` → project documentation

## Workflow

### 1. Data Collection
Collected launch records from:
- SpaceX API
- Wikipedia scraping

### 2. Data Preparation
- Cleaned missing values
- Standardized variables
- Structured datasets

### 3. Exploratory Data Analysis
Analyzed:
- Launch success trends
- Payload relationships
- Launch site performance

### 4. Visualization
Built:
- Interactive charts
- Geographic maps

### 5. Machine Learning
Trained classification models to predict booster landing success.

## Results

- Launch site selection significantly affected landing success probability
- Payload mass showed an observable correlation with successful landings
- Interactive dashboard enabled exploration of launch outcomes
- Machine learning models achieved reliable classification performance

## Future Improvements

- Deploy dashboard
- Improve ML performance
- Add advanced feature engineering
- Expand launch history coverage
