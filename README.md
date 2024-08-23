English Premier League
The Premier League, often referred to as the English Premier League or the EPL outside England, is the top level of the English football league system. It is Contested by 20 clubs every season.
Goal
To predict the result of every fixture
Dataset
Dataset is taken from https://www.football-data.co.uk/englandm.php
I make use of five seasons, which consist of 26 teams  during this period 
Colunms:
* Date = Match Date (dd/mm/yy)
* HomeTeam = Home Team
* AwayTeam = Away Team
* HTHG = Half Time Home Team Goals
* HTAG = Half Time Away Team Goals
* HTR = Half Time Result (H=Home Win, D=Draw, A=Away Win)
* FTHG = Full Time Home Team Goals
* FTAG = Full Time Away Team Goals
* FTR = Full Time Result (H=Home Win, D=Draw, A=Away Win)
* HS = Home Team Shots
* AS = Away Team Shots
* HST = Home Team Shots on Target
* AST = Away Team Shots on Target
* HC = Home Team Corners
* AC = Away Team Corners
* HF = Home Team Fouls Committed
* AF = Away Team Fouls Committed
* HY = Home Team Yellow Cards
* AY = Away Team Yellow Cards
* HR = Home Team Red Cards
* AR = Away Team Red Cards

Split data to Training and Test sets
Create models
•	RandomForestClassifier 
•	DecisionTreeClassifier 
•	Support Vector Machine (SVM)
•	 XGBoost and 
•	LightGBM.  
Train and evaluate the models
•	Assess the performance of the models using metrics such as accuracy, precision, recall, F1-score, and mean squared error. Fine-tune the models to improve their performance.
•	Confusion Matrix and Classification Report

