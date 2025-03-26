# Django-based-House-Price-Prediction-
# 🏡 House Price Prediction with Django & Machine Learning

## 🚀 Project Overview
This project predicts house prices based on **property type, location, number of bedrooms, area size, and other factors**. It includes:
- **Machine Learning model** for price prediction.
- **Django backend** to serve the model and handle API requests.
- **Dynamic City-Location Selection** to prevent invalid inputs.
- **MongoDB (Optional)** for database integration.

---

## 📂 Create & Activate Virtual Environment
# For Windows
python -m venv venv
venv\Scripts\activate

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate
## Install Dependencies
pip install -r requirements.txt

##  How to Train the Model from Scratch
 Prepare Data
Ensure you have a dataset in CSV format (e.g., house_prices.csv).

Your dataset should have columns like:
property_type,price,location,city,baths,purpose,bedrooms,area_in_marla
## Train the Model
Run the following command to train the model:
python prediction/ml_model/train.py

## Download Model and use in django Project
