# House Price Prediction System

## Overview
A machine learning application that predicts property prices based on location, size, number of bedrooms, and amenities using real estate data.

## Business Problem
Buyers and sellers need accurate property valuations. This tool provides instant price estimates, helping buyers make informed decisions and sellers price their properties competitively.

## Tech Stack
- **Python**: Pandas, NumPy, Scikit-learn
- **Machine Learning**: Random Forest Regressor
- **Preprocessing**: OrdinalEncoder, LabelEncoder
- **Web Framework**: Flask
- **Frontend**: HTML, CSS

## Features
- Predicts house prices based on user inputs
- Considers location, square footage, BHK, bathrooms, and amenities
- Clean web interface for easy data entry
- Instant price prediction with INR formatting

## Model Performance
- **Algorithm**: Random Forest Regressor
- **Accuracy**: 96.2% (R² score)
- **Key Features**: Location, total square feet, number of bedrooms, bathrooms
- **Preprocessing**: Categorical encoding, feature scaling

## Key Insights
- Location is the strongest predictor of price
- Square footage has strong positive correlation with price
- Diminishing returns after 4 BHK
- Properties with balconies command ~5-10% premium

## Dataset
Real estate dataset with:
- Location/area name
- Property size (sqft)
- Number of bedrooms (BHK)
- Number of bathrooms
- Amenities (balcony, parking, etc.)
- Price (target variable)

## How to Run
```bash
# Install dependencies
pip install pandas numpy scikit-learn flask

# Run application
python app.py

# Access at
http://localhost:5000
```

## Model Details
- Handled missing values using median imputation
- Encoded categorical variables (location, amenities)
- Removed outliers using IQR method
- Split data 80-20 for training and testing
