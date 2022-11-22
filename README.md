This repo contains a project that predict house rental prices for the AirBnB dataset - an online marketplace for rental house, to serve the project for my Data Scientist course. In addition, I also write a blog about the insights I got after doing this project.

<b>Project Motivation</b>

After selecting the data airbnb - dataset around rentals and in fact, house prices seem to be dynamic and logically it will be affected by some house characteristics such as bigger houses -> high prices,… so I’m curious about the following questions and I work on this project to answer all of these:

Is it possible to predict the price of a house based on its characteristics
Which characteristics are most influential?
The correlation of those features with the rental price of the house.

<b>Acknowledgements</b>

Dataset used in this project is part of Airbnb Inside, and the original source can be found here.

Also this project follows the CRISP-DM process that I read in here.

<b>Description</b>

This includes the main file containing the code - SeattleAirBnB.ipynb and dataset files.

In which I use supporting libraries such as:

numpy and pandas - a data processing and calculation library
seaborn and matplotlib - a library that supports data visualization
scikit learn - a library that supports machine algorithms learning as well as model evaluation (In this project I use Linear Regression and Random Forest algorithms)

<b>Summary of the results</b>

After data understanding, exploring and cleaning, I finally selected some features that seem to affect the rent, built a model and looked at its parameters, the results showed R squared ~ 60%, showing the correlation of the selected features with the price, as well as the MAE, MAPE information is in the acceptable range.

In the next version of this project, I will use other algorithms as well as tuning parameters to improve the results of the model.
