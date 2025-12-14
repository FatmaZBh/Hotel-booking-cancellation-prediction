# Hotel Booking Cancellation Prediction

## Overview
This project analyzes hotel booking data to predict cancellations and identify customer segments in order to reduce revenue loss and improve overbooking and pricing strategies.

## Objectives
- Predict whether a booking will be canceled  
- Identify key factors influencing cancellations  
- Compare multiple machine learning models  
- Segment customers based on booking behavior  

## Dataset
- Hotel Booking Demand dataset  
- ~119,000 bookings  
- Target variable: `is_canceled`

## Methodology
- Data cleaning and feature engineering  
- Exploratory data analysis  
- Supervised learning (Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting)  
- Unsupervised learning (K-Means clustering, PCA)

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Hotel_Booking_Cancellation_Prediction.ipynb
