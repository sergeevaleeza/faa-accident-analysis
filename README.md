# FAA Accident and Incident Data Analysis

This project analyzes general aviation accident and incident reports from the FAA/NTSB to uncover trends, identify risk factors, and build predictive models to support aviation safety and data-driven decision-making.

## Overview

The goal of this project is to:

- Analyze historical aviation accident data.
- Identify top causes and trends in general aviation (GA) incidents.
- Explore the impact of weather, aircraft type, flight phase, and other variables.
- Use machine learning to predict the severity of accidents.
- Build visualizations and/or dashboards for interactive data exploration.

## Data Sources

- [NTSB Aviation Accident Database](https://www.ntsb.gov/_layouts/ntsb.aviation/index.aspx)
- [BTS Aviation Data](https://www.transtats.bts.gov/)

## Project Structure

faa-accident-analysis/
├── data/
│   ├── raw/              # Original downloaded datasets
│   └── processed/        # Cleaned CSVs or SQLite files
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_visualization.ipynb
│   └── 03_modeling_prediction.ipynb
├── scripts/
│   ├── clean_data.py     # Modular script version of data cleaning
│   └── utils.py          # Reusable functions (e.g., text parsing)
├── reports/
│   └── summary_report.pdf  # Final presentation/report
├── dashboard/            # Streamlit or Tableau project files
├── README.md
├── requirements.txt
└── .gitignore

## Key Questions

- What are the most common contributing factors to aviation accidents?
- How do accident rates vary by aircraft type, flight phase, and environmental conditions?
- Can we predict the likelihood of a fatal outcome based on known variables?

## Technologies Used

- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebooks
- NLP (for analyzing narrative text fields)
- Streamlit or Tableau (optional dashboard)
- Git & GitHub

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/faa-accident-analysis.git
   cd faa-accident-analysis
