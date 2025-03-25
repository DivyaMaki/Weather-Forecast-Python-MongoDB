# Weather Forecast Application

## Overview

This tool helps users analyze logistics data, offering insights into supplier performance, trip classifications, material bookings, clustering patterns, and vehicle efficiency. Results are displayed in an interactive GUI with visualizations like pie charts, bar graphs, and scatter plots.

## Installation

### Prerequisites

   * Python 3.8 or higher

   * Git (optional, for cloning)
     
   * Clone the Repository
     
     ```
     git clone https://github.com/DivyaMaki/Weather-Forecast-Python-MongoDB.git
     cd data-analysis-tool
     ```
     
## Install Dependencies Create a requirements.txt with:

   * pandas
   * matplotlib
   * scikit-learn
   * seaborn
     
Run the Tool

```
python app.py
```


> Note: You’ll need a CSV file (e.g., Delivery_truck_trip_data.csv) with columns like BookingID_Date, supplierNameCode, and vehicleType.


Usage

> Launch the app: python app.py

* Choose an analysis type from the dropdown menu.

* Upload a CSV file and enter any required inputs (e.g., dates, column names).

* View results in the GUI, including text summaries and charts.

Example

## To analyze vehicle efficiency:

   * Select "Vehicle Distance and Fuel Consumption Calculator."

   * Load your CSV.

   * Enter a date range (e.g., 01-01-2025 to 31-01-2025).

   * Click "Calculate" to see distance and fuel stats with a bar chart.

## Features

### Supplier Accuracy Classification

   * Tracks on-time and delayed deliveries by supplier.

   * Shows top 10 performers in pie charts.

### Trip Classification

   * Classifies trips as "Market" or "Regular" using Naive Bayes.

   * Includes a confusion matrix and customer booking bar charts.

### Material Booking Analysis

   * Summarizes material shipments by supplier and customer.

   * Displays counts in a horizontal bar graph.

### KMeans Clustering

   * Clusters data by supplier and location (state).

   * Visualizes results in scatter plots for "Market" and "Regular" trips.

### Vehicle Distance and Fuel Consumption

   * Calculates total distance and fuel use by vehicle type.

   * Presents data with a bar chart.

## Requirements

   * Python: 3.8+

   ### Libraries:

   * pandas - Data processing

   * matplotlib - Visualizations

   * scikit-learn - Machine learning

   * seaborn - Enhanced plotting

   * tkinter - GUI (included with Python)

Install with:

```
pip install pandas matplotlib scikit-learn seaborn
```
