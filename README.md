# GA-capstone-restaurant-reviews
### General Assembly Data Science Immersive Capstone - Analysis of Bias in London Restaurant Reviews

As a half italian who grew up around restaurants I appreciate good hospitality and food. However, like most of us, I find that online ratings for restaurants cannot be taken at face value. This led me to explore bias in London restaurant ratings using data science.  

I was particularly keen to test my hypothesis that the location of a London restaurant influences the average score it receives. This knowledge could be useful for building more accurate restaurant recommendation engines.  

In this repository you can see the data I’ve considered so far which has been gathered from a number of sources (including web scraping with Selenium and Beautiful Soup), and how I wrangled, analysed and visualised it using Python (particularly the Pandas, MatplotLib and Seaborn libraries) and Tableau. 

I have used a variety of supervised and unsupervised machine learning and statistical techniques to both create new restaurant features and measure the influence of factors on general scoring tendencies:
- Clustering Algorithms - to search for a new feature to better represent location and density than the original features.
- Regression and Classification modelling - to measure and compare feature importances.
- Hypothesis testing - to analyse whether there is a statistically significant difference between review scores from zone 1 (London's central zone) compared to outer zones.

The key challenge in this project has been how to best represent and measure bias with available data. I've come at this from a number of angles, looking at both critic and user scores and more than one review website.  There are many further avenues to explore in the future.