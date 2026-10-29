# Automatidata — NYC Taxi Tip Analysis & Machine Learning

**Data Analytics portfolio project | Python · Pandas · Scikit-learn · EDA · Random Forest**

## Summary
This project examines a sample of **22,699 NYC taxi trips (2017)** and builds a reproducible classification baseline to explore patterns associated with tips of at least 20% among card-paid trips.

**Business question:** Can trip information available before completion help explain or predict tipping patterns? The analysis is educational and **must not be used to deny taxi service**.

## What I did
- Inspected and filtered the trip dataset and defined a clear target.
- Explored tip rates and pickup time patterns.
- Built a baseline and a Random Forest classifier with train/test separation.
- Evaluated accuracy, precision, recall, F1 and a confusion matrix.
- Discussed data limitations and ethical risks.

## Reproducibility
1. Download or clone this repository.
2. Install Python packages: `pip install -r requirements.txt`
3. Open `notebooks/Automatidata_NYC_Taxi_Portfolio.ipynb` with Jupyter, **from the repository root or notebooks folder**.
4. Run all cells in order. The CSV is provided at `data/2017_Yellow_Taxi_Trip_Data.csv`.

## Files
- `notebooks/Automatidata_NYC_Taxi_Portfolio.ipynb`: independent reproducible portfolio analysis.
- `notebooks/original_coursera_lab.ipynb`: original coursework preserved for reference; **it requires the separate `nyc_preds_means.csv` file, which was not available**.
- `data/2017_Yellow_Taxi_Trip_Data.csv`: 2017 taxi-trip dataset supplied with the coursework.

## Important distinction
This portfolio notebook was **adapted from my Automatidata coursework** and uses a newly defined feature set. It does **not** reproduce the exact Random Forest or XGBoost results from the original notebook; it does not fabricate `nyc_preds_means.csv` or claim that the original model was reproduced. Dataset provenance should be reviewed before any secondary use.

## Ethics and limitations
Tip data are recorded mainly for card payments, and some future or trip-end information is unavailable at booking. These predictions should be used only as a learning exercise or to study *aggregated* patterns, not to screen individual customers or deny services.

## Author
Jonathan — Data Analyst | Iquique, Chile · [LinkedIn](https://www.linkedin.com/in/jonathan-diac-c-b0a749381/)
