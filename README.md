# Reinforcement Learning Using UCB and Thompson Sampling 

Created a Reinforcement Learning Model to choose the best advertisement to display on several websites during an Ad-campaign.   Used Upper Confidence Bound algorithm to create a baseline and Thompson Sampling to improve the online learning model that came up with the best ad from a group of 10 similar advertisements in far less time, which is required for multiple AB tests, and maximized click through rate.

Attached Data File is a preprocessed simplified file that contains rewards as columns for each ad. 
Each index/row is a round in which those 10 Ads were displayed.
Reward columns have 1 if the ad is clicked during that round else 0.
