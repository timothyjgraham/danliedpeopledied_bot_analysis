# danliedpeopledied bot analysis

DanLiedPeopleDied hashtag analysis 
We collect 5000 latest tweets and run a state-of-the-art bot detection model:
https://github.com/mkearney/tweetbotornot2

This repo contains code to collect data, run the bot detection model, and examine which user accounts have a greater than 0.5 probability of being bots.

It also contains a CSV file with tweet IDs, providing the ability to reproduce the findings by collecting the same dataset.

Out of 2,082 unique user accounts, only two accounts are likely to be bots. 
