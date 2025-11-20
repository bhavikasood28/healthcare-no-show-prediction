# Healthcare Appointment No-Show Prediction and Cost Analysis

This project analyzes outpatient appointment data to understand drivers of patient no-shows, predicts no-show risk using machine learning, and estimates the operational and financial impact for a typical U.S. healthcare provider. The work is structured similar to analytics engagements delivered by major consulting firms.

## Project Objectives

* Predict the likelihood of a patient not attending a scheduled appointment.
* Identify key variables influencing no-show behavior.
* Estimate revenue loss associated with missed appointments.
* Simulate scheduling strategies, such as risk-based overbooking and targeted reminders.
* Provide results and insights through a simple interactive dashboard.

## Background

No-shows create operational inefficiencies and significant financial loss for healthcare systems. This project uses a publicly available dataset to replicate a common consulting use case: improving scheduling performance through predictive analytics and scenario modeling.

## Data

Primary dataset: Medical Appointment No-Shows (Kaggle), containing patient demographics, appointment details, reminder indicators, and historical outcomes. Financial assumptions are based on widely used outpatient benchmarks.

## Methodology

1. Data cleaning and exploratory analysis.
2. Feature engineering (wait times, appointment timing, demographics, prior behavior).
3. Model development using logistic regression, random forest, and gradient boosting.
4. Cost estimation using predicted no-show probabilities.
5. Scenario simulation of scheduling interventions.
6. Dashboard development for interactive review.

## Repository Structure

```
data/
notebooks/
src/
dashboard/
reports/
presentation/
configs/
requirements.txt
```

## How to Run

Install dependencies:

```
pip install -r requirements.txt
```

Run the dashboard:

```
streamlit run dashboard/app_streamlit.py
```
