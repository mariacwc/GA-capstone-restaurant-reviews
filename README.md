# GA-capstone-restaurant-reviews
### General Assembly Data Science Immersive Capstone - Analysis of Bias in London Restaurant Reviews

As a half italian who grew up around restaurants I appreciate good hospitality and food. However, like most of us, I find that online ratings for restaurants cannot be taken at face value. This led me to explore bias in London restaurant ratings using data science.  

I was particularly keen to test my hypothesis that there is a detectable influence on the average rating a London restaurant receives based on metadata such as its location. This knowledge could be useful for building more accurate restaurant recommendation engines.     

The key challenge in this project has been how to best represent and measure bias with available data. In this repository you can see the ratings and metadata I’ve considered so far which has been gathered from a number of sources (including web scraping with Selenium and Beautiful Soup), and how I wrangled, analysed and visualised it using Python (particularly the Pandas, MatplotLib and Seaborn libraries) and Tableau. 

I have used a variety of supervised and unsupervised machine learning and statistical techniques to both create new restaurant features and measure the influence of factors on general scoring tendencies:
- Clustering Algorithms - to search for a new restaurant feature to better represent its location than London Transport Zones.
- Regression and Classification modelling - to measure and compare feature importances and inconsistency between critic and user ratings.
- Hypothesis testing - to analyse whether there is a statistically significant difference between review scores from zone 1 (London's central zone) compared to outer zones.

The project has given me many interesting insights into the London Restaurant scene. The modelling and hypothesis testing showed a small but statistically significant location factor influence as well as identifying the restaurant features which most impact average user ratings.  My appetite to use this project to keep learning remains unsatiated, future project plans include utilizing Natural Language Processing for sentiment analysis and new feature creation and building a basic recommendation engine
