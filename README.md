# NBA-Win-or-Lose-Prediction

**Project:**
Predicts NBA Games Using a Logistic Regression Model in Python

**Model**
This project uses 8 factors scraped from stats.nba.com to determine the predicted result of an NBA game. Each stat is adjusted to per 100 possessions to ensure pace has no impact on the predictions.

**Factors**
- Home Team
- Win Percentage
- Rebounds
- Turnovers
- Plus Minus
- Offensive Rating
- Defensive Rating
- True Shooting Percentage


**Usage**

       1. Installation
            pip3 install -r requirements.txt

       2. Daily Predictions
          - Open nbaPredict.py
          - Edit the call to makeInterpretPrediction with desired date of games, season, and the 
            start date of the season NBA-Predict Image
          - Run the program either through the terminal or an IDE
          - Wait ~1-3 minutes for model to finish scraping stats and predicting outcomes
          - Outcomes are outputted as the percent chance that the home team will defeat 
            the away team

       3. Past Predictions
          - Open makePastPredictions.py
          - Edit the call to makePastPredictions with desired start date, end date, season, start 
            date of the season, and output filenames. NOTE: The start date should be at least 
            three days after the season begins and the end date is non-inclusive.
          - Run the program either through the terminal or an IDE

          - Two CSV files will be saved in the Data folder. One holds the gameData and the other 
            holds the predictions for the games. The time to execute will vary greatly from a 
            couple minutes to a several hours depending on the range between the start and end date.

