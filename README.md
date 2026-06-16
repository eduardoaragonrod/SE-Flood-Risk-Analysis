# Southeast U.S. Flood Risk Analysis

## Overview
This repository contains the work for my internship project focused on analyzing and visualizing historical flood inundations across the Southeastern United States. The project leverages satellite observational data from the Dartmouth Flood Observatory (DFO) spanning from 2003 to 2024. 

The goal of this project is to process large geospatial datasets and provide an interactive web dashboard for researchers to explore flood events, their duration, and their human impact (such as displacement and fatalities) across specific states and time periods.

## Project Structure
The repository is organized into data processing and visualization components:

* **`data_raw/`**: Contains the original, unprocessed datasets (Ignored in version control due to file size constraints).
* **`data_clean/`**: Contains the cleaned and filtered subset of the DFO data used for the application (`DFO_Southeast_2003_2024.csv`).
* **`notebooks/`**: Jupyter notebooks detailing the data cleaning pipelines, exploratory data analysis (EDA), and geospatial transformations using Python (Pandas/GeoPandas).
* **`src/`**: The frontend React application that serves as the interactive dashboard for the cleaned data.

## Features
* **Interactive Web Map**: Visualizes historical flood polygons using Leaflet.
* **Temporal Filtering**: A timeline slider to query flood events between 2003 and 2024.
* **Spatial Filtering**: Toggleable state filters (Florida, Georgia, South Carolina, North Carolina, Alabama, Mississippi, Virginia) with "Match Any" or "Match All" inclusion logic.
* **Impact Statistics**: Calculates aggregate statistics functionally based on active filters, including total displaced populations and average flood duration.

## Technologies Used
* **Data Processing**: Python, Jupyter Notebooks, Pandas, GeoPandas.
* **Frontend Dashboard**: React, TypeScript, Vite.
* **Geospatial UI**: React-Leaflet, rc-slider, Tailwind CSS.

## Getting Started

### Prerequisites
* Node.js (v18+)
* Python 3.8+ (for notebook execution)

### Running the Dashboard Locally
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required Node dependencies:
   ```bash
   npm install
