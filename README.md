# VCT Americas '24 ML Predictions

Using BeatifulSoup to scrap data on 2024 season Valorant esports matches makes predicitons about upcoming matches at the end of the season using Scikit Learn's machine learing models about upcoming matches at the end of the season.

VCT Americas is a series of tournaments for the top professional Valorant esports teams from North and South America to compete for a chance to play at the international level. 

Data:

This project aims to predict the winner of a upcoming match up given the teams playing and the in game map they are playing on. Data for this project was scraped using BeatifulSoup and put into a Pandas dataframe. The data was then cleaned and preped for machine learing. 

Models:

Two models from SciKit Learn were tested for this model. First was the RandomForestClassifier. Using this model an accuary score of 62% was achieved and a precision score of %92. The LinearSVC yielded lower scores, so RandomForestClassifier was prefered. 

Files:
The scrpaing file contatains the python code used to scraping data and format the data into a CSV. The predictions file implement the models from SciKit learn to make predictions based off the data compiled in the other file. 
