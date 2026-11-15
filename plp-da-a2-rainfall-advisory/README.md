# County Rainfall and Planting Advisory

**Full name:** Ramadhan Fatuma Soud

**Cohort:** 1 Million Devs for Africa Software Engineering course - 1 Million Devs Cohort

## Project summary

A farmer-support NGO sends SMS advice on planting windows in five counties. The project cleans one hand-typed station row for Machakos and combines it with four clean rows into one NumPy array. It then calculates annual totals and monthly averages and wettest months and dry months and planting windows. The results save to `rainfall_summary.csv`.

## How to run the notebook

How to run: open `rainfall_analysis.ipynb` in Google Colab with the badge below then choose Runtime and Run all.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fatmaram/plp-da-a2-rainfall-advisory/blob/main/rainfall_analysis.ipynb)

To run it on your own computer:

1. Install the library with `pip install -r requirements.txt`
2. Open `rainfall_analysis.ipynb` in VS Code or Jupyter
3. Choose Run All. The notebook writes `rainfall_summary.csv` in the same folder.

## Planting advisory

- Plant in April and May in Nairobi and Nakuru and Kisumu and Mombasa because that window brings the most rain in all four counties with 265 mm to 420 mm.
- Plant in November and December in Machakos where 278 mm falls in two months and prepare for 6 dry months below 50 mm with drought-tolerant seed and water storage.
- Treat the Machakos annual total of 811 mm with caution because two invalid readings for April and September were replaced with the county average of 68 mm.

## Files

- `rainfall_analysis.ipynb` holds the cleaning and analysis with all outputs visible.
- `rainfall_summary.csv` holds one row for each county.
- `requirements.txt` lists the library used.
- `README.md` holds the summary you are reading.