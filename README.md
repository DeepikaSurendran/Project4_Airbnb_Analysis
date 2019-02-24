# Project4_Airbnb_Analysis

#Motivation

This is the Project as part of the DSND with Udacity . The Data used in the Project is from Kaggle .
Questions analysed as part of the project is

Question 1: How are the pricing of the properties in Boston and Seattle? Are there any events that cause hike in price?

Question 2: How is the availability of the properties in both cities throughout the year

Question 3: Do the comments of the visitors on a listing give us enough information  to guess the review score of that listing

#Installations

Below are the some of the installations needed
Python 3.6.5 Anaconda Distribution
[nltk] (https://www.nltk.org/data.html)

#File Descriptions
calendar.csv and calendar_boston.csv - csvs containing home_id, availability, and price for every listing/date combination

listings.csv and listings_boston.csv - id, review_scores_rating for each listing

reviews.csv and reviews_boston.csv - csvs containing the home_id, date of review, reviewer_id, reviewer_name, and reviewer comments for the reviewed stays.


#Licensing, Authors, Acknowledgements
Data used are provided through Kaggle by AirBnB : Boston data on Kaggle and for the Seattle data.

#Summary of Result

Question 1 : How are the pricing of the properties in Boston and Seattle? Do they have seasonality? Are there any events that cause jumps in price?Yes we are seeing some price hike in the appartments when there is an event in the city'The average price during the Boston Marathon period in 2017 was $232'

Question 2: How is the availability of the properties in both cities throughout the year?
 'In Boston, at any given time, there is a %49 chance that a house is available, while in Seattle this figure is much higher at %67'

Question 3: Can we predict the review score from comments using regression? Do the comments of the visitors on a listing give us enough information for us to guess the review score of that listingour SGDRegressor model is performing quite well in predicting the scores from the comments provided.



#Medium Post : 
https://medium.com/@deepika.4413/understanding-the-market-of-airbnb-in-seattle-and-boston-5e4a4006030d
