# Applied Data Science Capstone – SpaceX Launch Prediction

## Overview

This repository contains the final project for the IBM Data Science Professional Certificate. The objective of this capstone is to apply data science methods to a real-world scenario involving SpaceX launch data. The project focuses on predicting the success of Falcon 9 rocket first-stage landings using public datasets and machine learning techniques.

## Problem Statement

SpaceX significantly reduces launch costs through the reuse of its rocket components, especially the first stage of the Falcon 9. Being able to accurately predict whether the first stage will land successfully can be essential for estimating costs and improving reliability.

## Key Questions

* How do payload mass, launch site, number of prior flights, and orbit type affect first-stage landing success?
* Has the success rate of landings improved over the years?
* What is the best-performing classification model for predicting landing outcomes?

## Project Structure

### 1. Data Collection

* SpaceX data retrieved from the SpaceX REST API.
* Additional historical launch data scraped from Wikipedia.

### 2. Data Wrangling

* Data filtering to remove irrelevant entries.
* Handling of missing values.
* Encoding of categorical variables using One-Hot Encoding.

### 3. Exploratory Data Analysis (EDA)

* Data exploration using SQL queries.
* Visual analysis using Python libraries such as Matplotlib and Seaborn.

### 4. Interactive Visualizations

* Folium used to create interactive maps of launch locations.
* Plotly Dash used to build a dashboard for exploring launch data interactively.

### 5. Predictive Modeling

* Applied classification algorithms including Decision Trees, Logistic Regression, Support Vector Machines, and K-Nearest Neighbors.
* Model tuning and evaluation performed using accuracy metrics on validation and test datasets.

## Technologies Used

* Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Plotly, Dash)
* SQL (via Jupyter Notebook with `%sql` magic)
* Folium (for mapping)
* Git & GitHub

## Results

The final model selection and evaluation are included in the notebook. The best-performing classifier achieved significant accuracy in predicting first-stage landing success.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/spacex-landing-prediction.git
   cd spacex-landing-prediction
   ```

2. Open the notebooks in Jupyter or JupyterLab.

3. Ensure you have all dependencies installed (see `requirements.txt` if included).

4. Run each notebook in order, starting from data collection to modeling.

## License

This project is part of the IBM Data Science Professional Certificate program and is licensed for educational use.
