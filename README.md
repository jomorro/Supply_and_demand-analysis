# Supply and Demand Analysis for Taxi Drivers and Riders
## Overview

This project analyzes the supply and demand dynamics of taxi services by examining the number of taxi drivers and riders per hour. Using Python’s pandas for data manipulation and Plotly for interactive visualizations, this project aims to provide insights into the patterns of taxi demand and supply over time.
## Features

* Load and preprocess data for taxi drivers and riders
* Analyze supply and demand trends per hour
* Visualize trends using interactive Plotly charts
* Compare the number of drivers and riders to identify patterns and discrepancies

## Prerequisites

* Python 3.7 or higher
* pip (Python package installer)

## Installation

1. Clone the repository:

        git clone https://github.com/yourusername/taxi-supply-demand-analysis.git

2. Navigate to the project directory:

        cd taxi-supply-demand-analysis

3. Create a virtual environment (optional but recommended):

        python -m venv venv

4. Activate the virtual environment:

        Windows: venv\Scripts\activate

        MacOS/Linux: source venv/bin/activate

5. Install the required packages:

        pip install -r requirements.txt

## Data

* CSV File: The project expects CSV files with hourly data for taxi drivers and riders. Ensure the files include columns such as Timestamp, Drivers, and Riders. Place these files in the data directory, named rides.csv, respectively.

## Results

* Supply and Demand Analysis: Analysis of the number of taxi drivers and riders per hour to identify trends and patterns.
* Visualizations: Interactive line plots showing the hourly trends of taxi drivers and riders, helping to understand supply and demand dynamics.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
## Acknowledgments

* Pandas for data manipulation and analysis.
* Plotly for interactive data visualization.
