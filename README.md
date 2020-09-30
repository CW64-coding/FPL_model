# FPL_model
This is a notebook which selects an optimised Fantasy Premier League (FPL) football team based on historical data.

This is done purely for my practise in machine learning and other techniques in Python.

Using historical full season statistics, I aim to create a machine learning model that uses a players stats in the previous year to predict their FPL points performance in the following season.

With these predictions we then use brute force to calculate the 15 person squad that offers the highest predicted total team score - subject to the constraints of the FPL rules.

Updates to the team (based on injuries/transfers) will also be made using the model. As the season progresses the model can be updated with current season data.

Note
This notebook assumes the reader has at least some familiarity with Python, machine learning, football and the Fantasy Premier League statistics (though rules and constraints are explained).
