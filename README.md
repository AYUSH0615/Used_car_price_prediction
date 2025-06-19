Used Car Price Prediction

This project provides a web application to predict the price of used cars based on various features. The application is built using Flask and leverages a machine learning model trained on a dataset of used car specifications.

Live Website
You can access the live prediction website here: https://web-production-6812.up.railway.app/

Features
User-friendly Interface: A clean and intuitive web form allows users to input car details for price prediction.
Comprehensive Input Fields: Predict car prices based on:
Car Name
Brand
Model
Vehicle Age (Years)
Kilometers Driven
Number of Seats
Seller Type
Fuel Type
Transmission
Mileage (km/l)
Engine (CC)
Max Power (BHP)
Machine Learning Powered: Utilizes a pre-trained machine learning model for accurate predictions.

Technologies Used
Frontend: HTML, CSS (implied by the web interface)
Backend: Flask (Python web framework)
Machine Learning: scikit-learn
Data Manipulation: pandas, numpy
Data Visualization (for development/analysis): matplotlib, seaborn
Model Persistence: joblib
Web Server Gateway Interface: gunicorn (for production deployment)

Model Training
The train_model.py script is responsible for training the machine learning model. It typically involves:

Loading the dataset (Dataset\cardekho_dataset.csv).
Performing data preprocessing (handling missing values, encoding categorical features, scaling numerical features).
Training a machine learning model (e.g., RandomForest, Gradient Boosting).
Saving the trained model and any necessary preprocessor objects (.pkl files) for later use by app.py.
