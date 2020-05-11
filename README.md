Expected Goals Deep Dive:

In this repository, I will build upon the brilliant work done by David Sumpter and @clekraus on expected goals as part of the Friends of Tracking series. 

David's tutorials: https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w/videos

David's code: https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython

@cleKraus' code: https://github.com/CleKraus/soccer_analytics

The repo will consist of 4 Jupyter notebooks, plus a notebook for reading in the Wyscout data and hand-constructing features that I believe will be helpful in building the model.

Notebook 1: Building a Random Forest Model for Expected Goals: In this notebook, we examine how to avoid overfitting/mistakes, learn how to cross validate our models and determine the best hyperparameters. Finally, we take a small section at the end to determine which features are important in a Random Forest.

Notebook 2: Comparing Logistic Regression and Random Forest For Expected Goals: In this notebook, we try to build the best logistic regression model, with a large emphasis on hand crafting features. Then, we examine the pros and cons of using logistic regression vs random forest for expected goals models.

Notebook 3: Calibrating an expected goals model: When our model spits out that a shot has a 30% chance it goes in, how do we know that that's accurate? In this notebook, we examine how to determine if our model's predicted probabilities are calibrated and tools to correct our model if we find that the probabilities are not calibrated.

Notebook 4: Building tools to showcase our logistic regression model: In this notebook, we leverage David's code for plotting expected goals models, and generate plots to help answer questions about our model, and try to find useful insights to show a coach or a player.

Data: For information on how to download the Wyscout data, please refer to David's video: Setting Up To Do Data Science.  In addition, please download the player data, as that is used  to determine the shooting player's favored foot. Please put the Wyscout data in the "Wyscout" folder of the repo to ensure that the code runs properly.


Special thanks to Wyscout for the data and FCPython for the code
