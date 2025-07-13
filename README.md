Applied Data Science Capstone

This capstone project serves as the final course in the IBM Data Science Professional Certificate program. It consolidates the key concepts and skills developed throughout the specialization into a comprehensive, real-world project.

Project Overview

The project centers around SpaceX, a leading private aerospace company known for making space missions more cost-effective. One major factor contributing to its cost savings is the reuse of the Falcon 9 rocket’s first stage. While a typical launch may cost around $62 million with SpaceX, competitors may charge more than $165 million per launch. Since reusability is a critical cost driver, predicting whether the first stage will successfully land is essential for estimating launch expenses. This project uses public data and machine learning to forecast the likelihood of a successful landing.

Key Research Questions

How do variables such as payload mass, launch site, number of previous flights, and orbit type impact the landing success of the first stage?
Has the frequency of successful landings improved over time?
Which classification algorithm provides the most accurate predictions for this scenario?
Approach and Methodology

Data Acquisition
Collected datasets from the official SpaceX API
Extracted supplementary data using web scraping from Wikipedia
Data Preparation and Cleaning
Applied filtering techniques to select relevant records
Handled missing values appropriately
Employed one-hot encoding to convert categorical features for binary classification
Exploratory Data Analysis (EDA)
Conducted EDA using visual tools and SQL queries to explore relationships in the data
Interactive Visual Analytics
Developed interactive maps with Folium
Built dashboards using Plotly Dash for dynamic data exploration
Predictive Modeling
Implemented various classification models
Tuned hyperparameters and evaluated model performance to identify the most effective algorithm for predicting first stage landings
