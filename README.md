# HealMetrics
A healthcare analytics project focused on leveraging cutting-edge technology to predict hospital length of stay (LOS) for patients. Utilizing Snowflake for data management and AWS SageMaker for machine learning, the project aims to improve patient care and optimize hospital resource utilization.
An end-to-end healthcare analytics project, demonstrating my expertise in data science. The project began with ETL processes in Snowflake, utilizing SQL queries and CTEs to handle raw data. AWS SageMaker was instrumental in preprocessing, feature engineering, and model development.
One of the project's key highlights was the integration of model predictions back into Snowflake, allowing for real-time accuracy comparison against a predefined threshold of 85%. To ensure ongoing model performance, I implemented an automated email notification system triggered by a scoring script, which alerts stakeholders if the model's accuracy falls below the set threshold.
This project exemplifies my ability to design and implement cloud-based solutions, leveraging tools such as Snowflake and AWS SageMaker. It marks a significant achievement in my data science journey, adding to my portfolio of projects that include TruthSeeker (NLP Project), GeoCabMatrix__RidePredictorX (Time Series forecasting Project), and Real-Time Hand Gesture Recognition Using ESP32 Rover Cam, Edge Impulse, and TinyML (ML + Embedded Systems Project). I am eager to apply these skills and experiences in my next role in data science.

![HealMetrics Image](https://github.com/AbhijithNidanakavi/HealMetrics/assets/91921508/4136df62-0a1d-425d-9c2b-20342332f74b)

# Architecture : 

![Healthcare Project Image](https://github.com/AbhijithNidanakavi/HealMetrics/assets/91921508/8b039f81-622f-4c90-8d1f-c2e9b939b20e)

# Approach:

   * Exploratory Data Analysis (EDA) in Snowflake
   * Feature Engineering within Snowflake
   * AWS SageMaker Configuration
   * Retrieving Data from Snowflake using snowflake-connector-python and snowflake-sqlalchemy
   * Data Preprocessing
   * Feature Selection
   * Model Development:
      * a. Linear Regression
      * b. Random Forest Regression
      * c. XGBoost Regression
   * Model Predictions
   * Insertion of Model Predictions into Snowflake
   * Deployment and Scheduling of Scoring Functions
   * Automated Status Email Notification
