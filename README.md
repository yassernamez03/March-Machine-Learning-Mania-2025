# March-Machine-Learning-Mania-2025
# March Machine Learning Mania 2025 - Competition Summary

 ## Overview
 The **March Machine Learning Mania 2025** Kaggle competition challenges participants to predict the outcomes of both the men's and women's 2025 NCAA Division 1 basketball tournaments. Participants are required to submit predictions for every possible matchup in the tournaments, using historical NCAA game data provided. The competition, now in its eleventh year, evaluates submissions using the **Brier score**, which measures the accuracy of probabilistic predictions (equivalent to mean squared error in this context).

 ## Key Details
 - **Objective**: Forecast the results of all possible matchups in the 2025 NCAA basketball tournaments.
 - **Data**: Historical NCAA game data is provided to build predictive models.
 - **Evaluation**: Submissions are scored using the Brier score, comparing predicted probabilities to actual game outcomes.
 - **Submission Format**: Participants must predict the probability of the team with the lower TeamId winning against the team with the higher TeamId for every possible matchup. The submission file includes predictions for both men's and women's tournaments.
 - **Leaderboard**: Prior to the 2025 tournaments, the leaderboard will reflect scores from 2021-2024. Once the 2025 games begin, Kaggle will update the leaderboard with actual results.

 ## Timeline
 - **Start Date**: February 10, 2025.
 - **Submission File Available**: Week of February 18-21, 2025.
 - **Final Submission Deadline**: March 20, 2025, 4PM UTC.
 - **Tournament Period**: March 20 - April 8, 2025, during which Kaggle will update the leaderboard as games are played.

 ## Prizes
 - **1st Place**: $10,000
 - **2nd Place**: $8,000
 - **3rd Place**: $7,000
 - **4th - 8th Place(s)**: $5,000

 ## Key Changes for 2025
 - Participants must predict outcomes for **all possible team matchups**, not just those selected for the NCAA tournament. This allows for earlier submissions and more time to refine predictions.
 - The competition combines predictions for both men's and women's tournaments into a single submission file.

 ## Submission Rules
 - Participants can submit multiple times before the tournament starts but must manually select the two submissions to be scored.
 - Submissions must follow the specified format, with unique game IDs and predicted probabilities.

## Example Submission Format
 ```csv
 ID,Pred
 2025_1101_1102,0.5
 2025_1101_1103,0.5
 2025_1101_1104,0.5
 ...
 ```
