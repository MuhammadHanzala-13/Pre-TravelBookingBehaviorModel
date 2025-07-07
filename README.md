# Customer Flight Booking Prediction Model

This repository contains a machine learning model to predict whether a customer will complete a flight booking, based on behavioral and booking data.

## Files Included

- `Pre-TravelBookingBehaviorMode.ipynb` – Jupyter Notebook with full code and results
- `Predicting Customer Booking Behaviour Model.pptx` – 1-slide summary for presentation
- `customer_booking.csv` – Source dataset used for modeling
- `lookups and Justification.xlsx` – Lounge eligibility logic (from Task 1)

## Model Summary

- **Model**: RandomForestClassifier
- **Accuracy**: ~85%
- **Top Features**: `booking_origin`, `flight_duration`, `length_of_stay`
- **Improvements**: Used SMOTE for class balancing and cross-validation for generalization

---
