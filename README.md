https://1drv.ms/p/s!AsE5lb7UH_SvuiLkB4-iS_CY9fM2

Song Success Analysis Project
Overview
This project aims to understand the factors contributing to a song's success. By analyzing data from various platforms, including Spotify, I investigate how different metrics and release timing impact the popularity of songs. The project employs machine learning models and data visualization techniques to uncover patterns and provide actionable insights.

Project Structure
The project follows the OSEMN (Observe, Scrub, Explore, Model, iNterpret) method for data science:

Observe: Initial data exploration to understand the datasets.
Scrub: Data cleaning to handle missing values and format issues.
Explore: Analyzing data patterns and relationships between features.
Model: Building and fine-tuning machine learning models to predict song success.
iNterpret: Interpreting results and creating visualizations to understand the findings.
Data
The dataset contains metrics from various platforms, including:

Spotify: Release date, number of streams, and other related features.
Other Platforms: Metrics such as Amazon's playlist count and SiriusXM spins.
Methodology
Data Cleaning
Handling missing values using techniques like SimpleImputer.
Ensuring consistent formatting across the datasets.
Feature Engineering
Creating new features such as 'Day of Week' based on the release date.
Exploratory Data Analysis (EDA)
Visualizing data to uncover patterns and relationships between features.
Using line plots to show the average Spotify streams by the day of the week.
Modeling
Building a Ridge regression model to predict track scores based on platform metrics.
Evaluating model performance using metrics such as R² score.
Results
Spotify Streams Analysis
The analysis revealed that the day of the week impacts Spotify streams, with higher streams towards the end of the week and over the weekend.
Visualizations highlight these trends, providing insights into how release timing influences song success.
Machine Learning Model
The Ridge regression model explained approximately 99.9% of the variation in track scores.
Important factors identified include Amazon's playlist count and SiriusXM spins.
Visualizations show that the model performs well but still has room for improvement.
Conclusion
The project provides valuable insights into the factors that influence a song's success. By understanding patterns in Spotify streams and other platform metrics, artists and marketers can make informed decisions to optimize the performance of their releases. The analysis highlights the significance of release timing and specific platform metrics in determining a song's popularity.

Documentation
Ridge Regression: scikit-learn documentation
Random Forest Regression: scikit-learn documentation
Hyperparameter Tuning: GridSearchCV documentation
Exploratory Data Analysis: Seaborn documentation
Data Cleaning and Manipulation: Pandas documentation
Authors
Pedro Luiz Resende Quartiero (July 24)
