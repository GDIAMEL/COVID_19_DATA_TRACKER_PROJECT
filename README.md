# COVID_19_GLOBAL_DATA_TRACKER_PROJECT

A comprehensive Python application for tracking, analyzing, and visualizing global COVID-19 data.

## Project Overview

This COVID-19 Global Data Tracker is designed to fetch, process, analyze, and visualize pandemic data from reliable sources. It provides insights into global trends, country-specific metrics, and important statistical indicators to help understand the impact and progression of the pandemic.

## Features

- **Data Collection**: Automatically fetches the latest COVID-19 data from Johns Hopkins University CSSE GitHub repository
- **Global Analysis**: Tracks confirmed cases, deaths, recoveries, and active cases worldwide
- **Country-level Analysis**: Provides detailed metrics for individual countries
- **Visual Analytics**: Creates insightful visualizations including:
  - Global trend analysis
  - Top affected countries
  - Mortality and recovery rates comparison
  - Daily new cases analysis
- **Statistical Reports**: Generates comprehensive statistical summaries
- **Data Export**: Exports processed data to CSV format for further analysis

## Requirements

- Python 
- pandas
- matplotlib
- seaborn
- numpy
- requests

## Installation

1. Clone the repository or download the source code
2. Install the required packages:

## Getting Started
To run this project locally, follow these steps:

1. Clone the Repository

git clone https://github.com/GDIAMEL/COVID_19_DATA_TRACKER_PROJECT.git
cd COVID_19_DATA_TRACKER_PROJECT

### Running Comprehensive Analysis

For a complete analysis with all visualizations and reports saved to an output directory:

```python
tracker = CovidDataTracker()
tracker.run_comprehensive_analysis(output_dir="covid_analysis_output")
```

### Running the Demo

```bash
python covid_19_data_tracker.py
```

## Explanation of Key Files

- `covid_19_data_tracker.py`: Main module containing the `CovidDataTracker` class and all functionality


## Data Sources

This project uses data from the COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University:
- [COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19)

## Example Output

When running the comprehensive analysis, the following files will be generated in the output directory:

- `global_trend.png`: Line chart showing the progression of cases globally
- `top_countries_confirmed.png`: Bar chart of countries with the most confirmed cases
- `top_countries_deaths.png`: Bar chart of countries with the most deaths
- `top_countries_active.png`: Bar chart of countries with the most active cases
- `mortality_recovery_rates.png`: Comparison of mortality and recovery rates by country
- `daily_changes.png`: Analysis of daily new cases with a 7-day moving average
- `covid19_summary_report.csv`: Tabular data for all countries with key metrics
- `covid19_statistics.txt`: Text file containing summary statistics

## License

This project is provided for educational and informational purposes only.

## Disclaimer

This tool is not meant to provide medical advice or official COVID-19 guidance. Please refer to official health organizations such as the World Health Organization (WHO) or your local health authorities for accurate medical information and guidance.
