# What-makes-a-video-game-sucessfull-
1) Introduction and Background
The video game industry is a multibillion dollar global market, with thousands
of titles released each year. Some games become global sensations, while others
fail to attract attention. This project aims to explore which factors are most
strongly associated with a game’s success, defined by global sales and user/critic
ratings. Using data on genre, platform, critic/user scores, and ESRB ratings, we
will analyze what characteristics tend to predict higher game sales and reception.
2) Research Questions
• What are the most significant predictors of a video game’s global sales?
• Do games with higher critic or user ratings tend to sell better?
• Does game genre significantly influence a game’s commercial success?
• Are certain platforms more strongly associated with higher-performing
games?
3) Data Description
3.1 Dataset
Kaggle- Video Game Sales with Ratings
Source: https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings
3.2 Variables
Dependent Variables (Targets)
• Global Sales: Total worldwide sales, measured in millions of units.
• User Score: Average rating provided by users (typically on a scale from
0 to 10).
• Critic Score: Average rating provided by critics (typically on a scale
from 0 to 100).

Independent Variables (Predictors)
• Genre: Type or category of the game (e.g., Action, Strategy, Sports).
• Platform: The console or system on which the game was released (e.g.,
PlayStation, Xbox, PC).
• Publisher: The company that published the game.
• ESRB Rating: Content rating assigned by the Entertainment Software
Rating Board (e.g., E, T, M).
• Year of Release: The year the game was released.
• Critic Score: Used as a predictor when the target variable is Global
Sales.
• User Score: Used as a predictor when the target variable is Global Sales.
4) Methodology
To investigate the factors that influence the success of video games, we will
apply a combination of statistical techniques.
Descriptive Statistics
• Computesummarystatistics (mean, median, standard deviation) for global
sales and ratings.
• Use visualizations such as boxplots, histograms, and bar charts to explore
data distributions and detect patterns.
Hypothesis Testing and Confidence Intervals
• Conduct hypothesis tests to determine whether games with higher critic
scores have significantly higher global sales.
• Construct confidence intervals for the average sales in different genres.
Analysis of Variance (ANOVA)
• Examine whether the mean global sales differ significantly by game genre
or platform.
Multiple Linear Regression
• Develop a regression model to predict global sales based on key variables
such as genre, platform, ESRB rating, critic score, and user score.

Logistic Regression (Optional Extension)
• Classify games as “successful” (e.g., sales ¿ 1 million units) or ’not suc
cessful’ based on predictor variables.
5) Possible Outcomes
We anticipate several key findings from this analysis:
• Games with a higher score among critics and users are expected to have
higher global sales.
• Certain genres, such as action and sports, may be associated with greater
commercial success compared to others.
• Platform type (e.g., PlayStation, Xbox, Nintendo) could play a significant
role in a game’s performance.
In general, this analysis aims to provide valuable information on the character
istics that contribute to both commercial and critical success in the video game
industry.
