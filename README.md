# SE-Flood-Risk-Analysis

This repository contains my internship project focusing on the spatial and temporal analysis of flood inundations across the Southeast United States (from 2003 to 2024).

## Overview

The main objective of this project is to build an interactive dashboard and data pipeline to evaluate historical flood events. By combining historical **DFO (Dartmouth Flood Observatory)** data with **NRT (Near Real-Time)** satellite information, this project aims to identify underlying patterns and causal links related to severe flooding.

## Features

* **Interactive Web Dashboard**: A React and Leaflet-based map interface that allows users to filter geospatial flood data by year, affected states, and match criteria.
* **Data Processing**: Python and Jupyter Notebooks used for cleaning, combining, and preparing raw geospatial data.
* **Causal Link Analysis**: Integrating DFO and NRT datasets to train an AI model to uncover causal relationships in flood triggers.

## Repository Structure

* `src/` - Source code for the interactive frontend map dashboard.
* `data_clean/` - Processed, lightweight datasets like `DFO_Southeast_2003_2024.csv` used directly by the application and models.

## Technologies Used

* **Frontend**: React, TypeScript, React-Leaflet, Tailwind CSS
* **Backend**: Python, Jupyter, Pandas
