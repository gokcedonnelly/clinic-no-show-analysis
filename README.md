# Clinic Appointments — No-Show Analysis

**Course:** Final Project  
**Author:** Your Name  
**Repo:** This repository contains the code, data, and slides for my course project analyzing appointment no-shows at a (synthetic) clinic.

## Project Goal
Help a clinic reduce no-shows by understanding what factors (SMS reminders, wait time / lead time, prior no-shows, distance, weekend, rain) are associated with higher or lower no-show rates, and recommend operational changes.

## Dataset
- File: `data/clinic_appointments_en.csv`
- Unit: 1 row = 1 appointment
- Target: `no_show` (1 = did not show, 0 = showed)
- Key features: `age`, `gender`, `distance_km`, `lead_time_days`, `prior_no_shows`, `sms_reminder`, `weekend`, `rain`, `date`

## What’s Inside
- **`Milestone_Final.ipynb`** – One notebook combining:
  - **Milestone 2:** Exploratory Data Analysis (shape, columns, dtypes, `info()`, `describe()`, `head()/tail()/sample()`)
  - **Milestone 3:** Data Cleaning (types, NaNs, outliers via IQR capping, validity checks)
  - **Milestone 4:** Analysis answering 4+ questions with Python and plots
- **`data/`** – raw and cleaned CSVs
- **`docs/summary.md`** – 1-page executive summary
- **`slides/final_presentation.pptx`** – slide deck for a 5-minute talk

## Tools
Python, Jupyter, pandas, numpy, matplotlib.

## Key Questions Answered
1. What is the overall no-show rate?
2. Do **SMS reminders** reduce no-shows?
3. How does **lead time** (days between booking and appointment) relate to no-shows?
4. Do **prior no-shows** predict new no-shows?
5. Are **distance**, **weekend**, or **rain** associated with no-shows?

## How to Run
1. Clone/download the repo.
2. Put the CSV in `data/`.
3. Open `Milestone_Final.ipynb` and run all cells (Kernel → Restart & Run All).  
   The notebook saves `data/clinic_appointments_clean.csv`.

## License
Educational use.
