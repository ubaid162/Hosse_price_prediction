House Price Prediction

A Machine Learning web application that predicts house prices based on key features such as location, total square feet, number of bathrooms, and BHK.
This project is built using Random Forest Regressor, achieving an accuracy of 96.2%.

Overview

This project uses a regression model to estimate housing prices from input features.
It helps users understand how different parameters like location, size, and amenities influence the final price.
The project is integrated with a Flask web interface, allowing users to input details and get instant price predictions.


Features
🔹 Data preprocessing and encoding for categorical variables
🔹 Model training using Random Forest Regressor
🔹 Interactive web UI built with Flask
🔹 Real-time prediction results
🔹 Well-structured and modular project


Project Structure
House_price_prediction/
│
├── app.py                # Flask app
├── rf_model.pkl          # Trained Random Forest model
├── encoders.pkl          # Encoders for categorical columns
├── templates/
│   ├── index.html        # Input form
│   └── result.html       # Output display
├── static/               # CSS or image files
└── README.md             # Project documentation


Model Details
* Algorithm: Random Forest Regressor
* Accuracy: 96.2%

Key Features:
* area
* price_per_sqft
* location
* total_sqft
* bath
* bhk

Sample Prediction Flow
1. Enter details such as area, sqft, bath, and location.
2. The model processes input using encoders and the trained Random Forest.
3. The predicted house price is displayed instantly on the result page.


Future Improvements
* Add more cities/locations
* Integrate live datasets
* Enhance UI with visualization dashboards
* Add price trend analysis using Power BI

