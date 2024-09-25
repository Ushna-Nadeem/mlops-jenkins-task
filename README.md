# mlops-deployment-task

# Sweet or Savory Predictor

Welcome to the Sweet or Savory Predictor project! This web application uses a machine learning model to predict whether a food is sweet or savory based on its ingredient quantities.

## Overview

This project includes:
- Model Training: A machine learning model trained to classify food as sweet or savory based on ingredient quantities.
- Flask API: A backend API built with Flask to serve predictions.
- Frontend: A simple web interface to input ingredient data and view predictions.

## Project Structure

- `app.py`: The main Flask application file that serves the API endpoints.
- `model.py`: The script to train and save the machine learning model.
- `index.html`: The HTML file for the frontend interface.
- `requirements.txt`: A file listing the project dependencies.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## How to Use

- Enter Ingredient Quantities: In the web form, input the quantities of ingredients (flour, sugar, salt, butter) in grams, separated by commas.
- Submit Form: Click the "Predict" button to send the data to the server.
- View Prediction: The result will be displayed below the form, showing whether the food is predicted to be sweet or savory.
