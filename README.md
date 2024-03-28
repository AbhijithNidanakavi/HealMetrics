# HealMetrics
A healthcare analytics project focused on leveraging cutting-edge technology to predict hospital length of stay (LOS) for patients. Utilizing Snowflake for data management and AWS SageMaker for machine learning, the project aims to improve patient care and optimize hospital resource utilization. HealMetrics utilizes data and analytical techniques to enhance healthcare services and patient outcomes. A critical aspect of this project involves analyzing patient Length of Stay (LOS), which denotes the duration of patient spent in a healthcare facility. LOS
significantly impacts patient outcomes, healthcare expenses, and hospital capacity. Analyzing patient LOS enables healthcare providers to identify areas for enhancing care delivery and
cost reduction. By proactively identifying patients at risk of extended LOS, providers can ensure timely and efficient care, thereby improving patient outcomes and reducing expenses.

Approach:

   . Exploratory Data Analysis (EDA) in Snowflake
   . Feature Engineering within Snowflake
   . AWS SageMaker Configuration
   . Retrieving Data from Snowflake using snowflake-connector-python and snowflake-sqlalchemy
   . Data Preprocessing
   . Feature Selection
   . Model Development:
      a. Linear Regression
      b. Random Forest Regression
      c. XGBoost Regression
   . Model Predictions
   . Insertion of Model Predictions into Snowflake
   . Deployment and Scheduling of Scoring Functions
   . Automated Status Email Notification
