# Football_matches
# England Premier League and SPAIN LIGA BBVA football matches deep exploratory analysis and some modeling

# PURPOSE

Dataset contains various data from football leagues in Europe, matches and players. Two national football leagues (England Premier League and SPAIN LIGA BBVA) were picked to investigate further and deeper, find similarities and differences in those leagues (as they seemed quite different), also their the leader teams, goals scored (from various points: home, away games) and so on. The aim was to find which features from matches, teams, leagues in total could be good in predicting the winner of the certain match and the number of scored goals.

# DATA

Given in SQL tables, SQLite was used to extract data and form needed DataFrames.

# STRUCTURE:

- **EDA_final.ipynb**
Deep analysis of the England and Spain national football leagues, data extractions (**SQLite**)data cleaning, plotting from various points 
(**PLOTLY, Matplotlib, Seaborn, Squarify libraries**)feature engineering to prepare the final, clean data set for modeling. Inferential statistical analysis was proceeded.

- **Modeling.ipynb**

Logistic regression (multinomial) and KNN was used to predict the win/loss/draw outcome of the game. Assumptions of the logistic regression were check (VIF score, linear relationships and etc.). Linear regression was used to predict the the number of goals (assumptions checked). 
