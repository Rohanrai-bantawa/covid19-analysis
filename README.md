# COVID-19 Trend Analysis & Forecast

Exploratory data analysis and a 7-day forecast of global COVID-19 cases using Python.

## What this project does

- Cleans and explores daily country-level COVID-19 data (49,068 rows, 22 Jan 2020 - 27 Jul 2020)
- Plots confirmed, deaths, recovered and active cases over time
- Finds the most affected countries and compares them with line and bar charts
- Forecasts the next 7 days of confirmed, deaths, active and recovered cases using Facebook **Prophet**

## Key results

- Global confirmed cases grew from 555 (22 Jan 2020) to about 16.5 million (27 Jul 2020)
- Prophet's 7-day forecast projects global confirmed cases of roughly 17.5 million by early August 2020

## Tech stack

Python, pandas, matplotlib, seaborn, Prophet, Jupyter Notebook

## How to run

```bash
git clone https://github.com/<your-username>/covid19-analysis.git
cd covid19-analysis
pip install -r requirements.txt
jupyter notebook Covid19PROJECT.ipynb
```

Make sure `data/covid_19_clean_complete.csv` is present (see `data/README.md`).

## Project structure

```
covid19-analysis/
├── Covid19PROJECT.ipynb
├── data/
│   └── covid_19_clean_complete.csv
├── requirements.txt
└── README.md
```

## Author

Rohan Rai
