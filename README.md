# Kaggle-Santander-Customer-Transaction-Prediction
In this competition, Santander invites Kagglers to help it identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. Good initiation to the Banking Analytics :)

<img src="https://ichef.bbci.co.uk/news/660/cpsprodpb/144B7/production/_104872138_santander2.jpg" align="middle">

## COMPETITION AND DATA OVERVIEW:
Santander's competition is about predicting which clients are going to make a transfer in the future. The available dataset is split between train and test, with 200,000 clients in each and no missing values ( blessedly :) ). There are 200 variables available (0, 199), but no information about them is given other than the numbers they hold.

As far as we know, all variables are independent from each other to the extent that if we separate the clients that made the transfer from the clients that didn't, then shuffle their values, and put them all back together, it won't affect your prediction score.

So far, only a few teams were able to cross the 0.92 prediction score barrier. A lot of people tried many different ideas, and almost all of them failed. So, I hope you enjoy reading and implementing this notebook and that it may help you to join the 0.92 club.
