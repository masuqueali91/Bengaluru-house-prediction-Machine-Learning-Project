 # Bangalore House Price Prediction

A machine learning web application that predicts house prices in Bangalore based on property details such as location, total square feet, number of bedrooms, bathrooms, and balconies.

## Project Overview

This project uses supervised machine learning regression algorithms to estimate house prices in Bangalore. The dataset is cleaned, transformed, and used to train a prediction model.

The application allows users to enter property details and receive an estimated house price.

## Features

- Predict Bangalore house prices
- Data cleaning and preprocessing
- Missing value handling
- Outlier removal
- Feature engineering
- Location-based price prediction
- Machine learning model training
- Model evaluation using R2 Score, MAE, and RMSE
- Simple web interface using Streamlit

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Streamlit
- Joblib
- Git and GitHub

## Dataset Features

| Feature | Description |
|---|---|
| location | Area or locality of the property in Bangalore |
| total_sqft | Total area of the house in square feet |
| bath | Number of bathrooms |
| balcony | Number of balconies |
| bhk | Number of bedrooms |
| price | House price in lakhs |

## Project Workflow

1. Collected the Bangalore house price dataset.
2. Cleaned missing and inconsistent values.
3. Converted total square feet values into a numerical format.
4. Extracted BHK from the size column.
5. Removed outliers using price-per-square-foot analysis.
6. Applied one-hot encoding to location data.
7. Trained a machine learning regression model.
8. Evaluated model performance using MAE, RMSE, and R2 Score.
9. Built a Streamlit web application for predictions.

## Installation

Clone this repository:

```bash
git clone [https://github.com/your-username/bangalore-house-price-prediction.git](https://github.com/your-username/bangalore-house-price-prediction.git)
```

Move into the project folder:

```bash
cd bangalore-house-price-prediction
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## Run the Application

Run the Streamlit application:

```bash
streamlit run app.py
```

After running the command, open the local URL shown in the terminal, usually:

```text
http://localhost:8501
```

## Model Evaluation

Use the following metrics to evaluate the model:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R2 Score

Example:

```text
MAE: [Add your MAE score]
RMSE: [Add your RMSE score]
R2 Score: [Add your R2 score]
```

## Screenshots

Add screenshots of your Streamlit application here.

```text
screenshots/
├── home_page.png
└── prediction_result.png
```

## Future Improvements

- Add more property features such as parking, furnishing status, and age of property.
- Compare multiple models such as Linear Regression, Random Forest, and XGBoost.
- Deploy the application using Streamlit Community Cloud or Render.
- Add user authentication and prediction history.
- Connect the application to a database.

## Author

Masuque Ali

- GitHub: https://github.com/masuqueali91
- LinkedIn: https://www.linkedin.com/in/masuque-ali-48b3492a1
