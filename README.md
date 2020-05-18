Expected Goals Deep Dive:

In this repository, I will build upon the brilliant work done by David Sumpter and @clekraus on expected goals as part of the Friends of Tracking series. 

David's tutorials: https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w/videos

David's code: https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython

@cleKraus' code: https://github.com/CleKraus/soccer_analytics

The repo will consist of 4 Jupyter notebooks, plus a notebook for reading in the Wyscout data and hand-constructing features that I believe will be helpful in building the model.

Notebook 1: Building a Random Forest Model for Expected Goals: In this notebook, we examine how to avoid overfitting/mistakes, learn how to cross validate our models and determine the best hyperparameters. Finally, we take a small section at the end to determine which features are important in a Random Forest. 

Link to Notebook 1: https://github.com/andrewsimplebet/expected_goals_deep_dive/blob/master/1.%20Random%20Forest%20Cross%20Validation%20And%20Hyperparameter%20Tuning.ipynb

Notebook 2 (soon): Comparing Logistic Regression and Random Forest For Expected Goals: In this notebook, we take a look at building a logistic regression model, with an emphasis on comparing strengths/weaknesses and paint points to a Random Forest. We then  take a look at why traditional data science methodologies used thus far are not sufficient to building a strong expected goals model, and preview what will come in the rest of the series.

Link to Notebook 2: https://github.com/andrewsimplebet/expected_goals_deep_dive/blob/master/2.%20Basic%20Logistic%20Regression%20and%20Comparison%20To%20Random%20Forests.ipynb

Notebook 3 (soon): Calibrating Expected Goals Models: When our model spits out that a shot has a 30% chance it goes in, how do we know that that's accurate? In this notebook, we examine how to determine if our model's predicted probabilities are calibrated and tools to correct our model if we find that this is not the case.

Link to Notebook 3: https://github.com/andrewsimplebet/expected_goals_deep_dive/blob/master/3.%20Calibrating%20Expected%20Goals%20Models.ipynb

Data: For information on how to download the Wyscout data, please refer to David's video: Setting Up To Do Data Science.  In addition, please download the player and matches data, as these tables are used in various spots in the series. Please put the Wyscout data in the "Wyscout" folder of the repo to ensure that the code runs properly.


Special thanks to Wyscout for the data and FCPython for the code!
