# GA-capstone-restaurant-reviews
### General Assembly Data Science Immersive Capstone - Analysis of Bias in London Restaurant Reviews

As a half italian who grew up around restaurants I appreciate good hospitality and food. However, like most of us, I find that online reviews and ratings for restaurants cannot be taken at face value. This led me to explore bias in London restaurant reviews using data science.  For this initial project I have chosen not to explore detailed restaurant reviews, instead my focus has been on measuring the influence of restaurant location factors and general characteristics such as the type of cuisine on offer.

In this repository you can see the data I’ve considered so far which has been gathered from a number of sources (including web scraping with Selenium and Beautiful Soup), and how I wrangled, analysed and visualised it using Python (particularly the Pandas, MatplotLib and Seaborn libraries) and Tableau.  Features have been engineered to represent factors that could impact reviews and manage limitations in the data. 

I have used a variety of supervised and unsupervised machine learning and statistical techniques to both create new features and measure the influence of factors on general scoring tendencies:
- Clustering Algorithms - to search for a new feature to better represent location and density than the original features.
- Regression and Classification modelling - to measure and compare feature importances.
- Hypothesis testing - to analyse whether there is a statistically significant difference between review scores from zone 1 (the central zone) compared to outer zones.
