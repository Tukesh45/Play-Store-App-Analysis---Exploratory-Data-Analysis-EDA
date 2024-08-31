# Play-Store-App-Analysis---Exploratory-Data-Analysis-EDA
# Table of Contents
Introduction
Data Source
Objectives
Data Cleaning
Exploratory Data Analysis (EDA)
Results and Insights
Tools and Libraries Used
Conclusion
Future Work
References
# Introduction
This project involves conducting an Exploratory Data Analysis (EDA) on a dataset from the Google Play Store. The goal is to extract meaningful insights about the apps available on the platform, such as their ratings, reviews, categories, and installation numbers. This analysis will help in understanding the key factors that contribute to an app's success.

# Data Source
Play Store App Data: The dataset contains information on mobile apps available on the Google Play Store. Key features include app name, category, rating, reviews, size, installs, type (paid or free), price, content rating, genres, last updated, current version, and required Android version.
# Objectives
To analyze the distribution of apps across different categories.
To explore the relationship between app ratings and other features like size, price, and category.
To investigate trends in app installations and identify top-performing apps.
To analyze user reviews and sentiments to gauge overall satisfaction.
# Data Cleaning
Missing Values: Handled missing values by imputing them based on the median, mean, or mode, depending on the feature, or removing rows/columns with too many missing values.
Data Types: Ensured all columns have appropriate data types, such as converting 'Installs' to integers and 'Last Updated' to datetime.
Outliers: Detected and handled outliers, particularly in features like price, reviews, and installs, to ensure they do not skew the analysis.
Duplicates: Removed duplicate records to maintain data integrity.
# Exploratory Data Analysis (EDA)
Category Distribution: Visualized the distribution of apps across various categories to identify the most and least represented categories.
Rating Analysis: Analyzed the distribution of app ratings and identified factors contributing to high or low ratings.
Review Analysis: Conducted sentiment analysis on user reviews to determine overall satisfaction and identify common themes in feedback.
Installation Trends: Investigated the distribution of app installs to identify the most popular apps and explored correlations between installs and other factors like price, rating, and size.
App Size and Permissions: Explored the relationship between app size, required permissions, and user satisfaction, considering how these factors might influence an app's success.
# Results and Insights
Category Insights: Identified which categories dominate the Play Store and which are less saturated.
Rating Correlations: Discovered correlations between app ratings and features such as price, size, and category.
Installation Patterns: Uncovered trends in app installations, identifying key drivers of app downloads.
User Sentiment: Analyzed user feedback to identify strengths and weaknesses in popular apps, highlighting areas for improvement.
# Tools and Libraries Used
Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, NLTK (for sentiment analysis).
Visualization Tools: Used various visualization libraries in Python to create detailed and informative visualizations.
Colab Notebook: Utilized for organizing the analysis, writing code, and documenting findings.
# Conclusion
The EDA provided a comprehensive overview of the Play Store app landscape, highlighting key factors that contribute to an app's success. The insights gained can be used by developers to optimize their apps for better performance and by marketers to target potential users more effectively.
