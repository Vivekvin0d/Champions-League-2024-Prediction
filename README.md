# UEFA Champions League 2024: Predicting Semifinal and Final Winners



# Project Overview

This project aims on analyzing the current  and historical performances of the teams in the semifinals and using machine learning to predict the winners of the semifinals and the finals of the Champions League 2024 tournament. By examining team performance, player statistics, and historical trends, the project aims to offer insights into which teams are most likely to succeed in the final stages of the competition.


<img src="https://pbs.twimg.com/media/GLZe6Y4aUAAdoUj.jpg:large" alt="Champions League Trophy" width="700" height="700" />

# Motivation

The semifinals and finals of the UEFA Champions League are some of the most highly anticipated matches in world football.Predicting the winner is a challenge that combines data analysis, machine learning, and domain knowledge. This project not only showcases the application of data science in sports but also serves as an engaging way to enhance my skills in Python, data analysis, and predictive modeling.

# Tools and Techniques Used
- Excel
- Jupyter notebook
- Python
- Machine learning
- Exploratory Data Analysis
- Predictive Analysis
- ChatGPT
- Prompt engineering
- Web Scrapping
- Instant Data Scraper

# Data Collection

The dataset includes current historical match data from the UEFA Champions League, covering team performances, player statistics, match outcomes, and current year domeestic league match data of the four teams in the semifinals. It also includes the historical head to head match data of the teams playing the semi finals and finals.

Data of historical and current year champions league was scraped and collected from the UEFA's official site. Each teams domestic performances from the current year was scraped from each teams official site.
Historical head to head data and other relevent data's were sourced from wikipedia and other reputable football statistics sites.

The data scraped and collected was converted into excel sheets for organising, cleaning and transforming.

# Data Cleaning

The data is then organised, cleaned and transformed in excel to then upload into python, jupyter notebook for further analysis and predictions.

The following steps and process were used in excel to clean and transform the data.

- Deleted unwanted rows and columns
- Gave proper headings for each columns
- Changed the data types of necessary columns
- Formated the data
- Checked for any missing values using conditional formatting and filters
- Used split and concatinate functions to oraganise and transform data
- Prepared new columns and calculated fields using formulas and functions like (=IF(D2>E2,"W",IF(D2=E2,"D","L"))

Raw Data<img src="Images and Screenshots/Screenshot scraped raw data.png" alt="Champions League Trophy" width="100%" height="500" /> Cleaned Data<img src="Images and Screenshots/Screenshot Transformed data.png" alt="Champions League Trophy" width="100%" height="500" />

# Data Analysis
### Analysis Structure
- Semifinals -- Bayern Munich vs Real Madrid
- Semifinals -- Borussia Dortmund vs Paris Saint-Germain
- Finals -- Borussia Dortmund vs Real Madrid
Steps mentioned below were performed for each of the teams in the semifinals and the finals.  

#### Step-1
Analysis on current season champions league data.
#### Step-2
Analysis on historical champions league data.
#### Step-3
Analysis on player stats and performances of the current year champions league season.
#### Step-4
Analysis on the performances and form of each team during the whole season including domestic league, league cups and champions league performances till the semi finals.
#### Step-5
Analysis on head to head data of the teams playing each other in the semifinals and the finals.
#### Step-6
Preparing, combining and feature engineering the data for the predictions.
#### Step-7
Importing the predictive model and libraries needed for accuracy, precision and realiability of the model.
#### Step-8
Created a training and testing model and calculated the accuracy and precision of the model.
#### Step-9
Used the model created to predict the results of each match.

### Insights from the Analysis of the teams in the Semifinals -- Bayern Munich vs Real Madrid

- Real Madrid has higher average goals scored per game than Bayern munich in both the current season and historically in the champions league competition.
- Real Madrid also has the higher average goals conceded per game, both in current season and historically when compared to Bayern Munich in champions league.

<img src="Images and Screenshots/Screenshot 2024-08-27 214836.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205032.png" alt="Champions League Trophy" width="100%" height="500" />

- Both Real madrid and Bayern munich have won 7/10 games in this UCL season. Real madrid has not lost a single game whereas Bayern munich have lost one game. Real madrid had 3 draws whereas Bayern munich had 2 draws.

<img src="Images and Screenshots/Screenshot 2024-08-27 205128.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205323.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205159.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205212.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205339.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205353.png" alt="Champions League Trophy" width="45%" height="300" />

### Analysis on player performances of Bayern Munich's current UCL season

<img src="Images and Screenshots/Screenshot 2024-08-27 205413.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205504.png" alt="Champions League Trophy" width="100%" height="700" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205528.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205604.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205618.png" alt="Champions League Trophy" width="100%" height="500" />

### Analysis on player performances of Real Madrid's current UCL season

<img src="Images and Screenshots/Screenshot 2024-08-27 205638.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205655.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205713.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 205727.png" alt="Champions League Trophy" width="100%" height="500" />

#### Analysis on Bayern Munich's and Real Madrid's performances in all competitions this season

- Bayern Munich has scored and conceded more goals in this season than Real Madrid.
- Real Madrid has won more games in total this season and has lost fewer games when compared to Bayern Munich.
- Real Madrid has won more home games this season than Bayern Munich and lost none of their home games vs Bayern's 3 losses.
- Real Madrid also has more away wins and fewer away losses when compared to Bayern Munich in all competitions this season.

#### Analysis on total Head to Head matches between Bayern Munich and Real Madrid 

- Both teams have met 12 times before and Real Madrid has won 12 games, lost 11 and drawn 3 times.
- Bayern Munich has won 11 games, lost 12 and drawn 3 times.

### Insights from the Analysis of the teams in the Semifinals -- Borussia Dortmund vs Paris Saint-Germain

- Borussia Dortmund has higher average goals scored per game in the current season but historically Paris Saint-Germain has higher average goals scored per game in the champions league competition.
- Borussia Dortmund has the higher average goals conceded per game, both in current season and historically when compared to Paris Saint-Germain in champions league.

<img src="Images and Screenshots/Screenshot 2024-08-27 210943.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 210958.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211123.png" alt="Champions League Trophy" width="100%" height="500" />

- Both Borussia Dortmund and Paris Saint-Germain have won 5/10 games in this UCL season. Borussia Dortmund has lost 2 games whereas PSG has lost 3 games. Borussia Dortmund had 3 draws whereas PSG had 2 draws.

<img src="Images and Screenshots/Screenshot 2024-08-27 211009.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211137.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211024.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211057.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211154.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211207.png" alt="Champions League Trophy" width="45%" height="300" />

### Analysis on player performances of Borussia Dortmund's current UCL season

<img src="Images and Screenshots/Screenshot 2024-08-27 211226.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211241.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211257.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211312.png" alt="Champions League Trophy" width="100%" height="500" />

### Analysis on player performances of PSG's current UCL season

<img src="Images and Screenshots/Screenshot 2024-08-27 211453.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211511.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211532.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211549.png" alt="Champions League Trophy" width="100%" height="500" />

#### Analysis on Borussia Dortmund's and PSG's performances in all competitions this season

- PSG has scored more goals in this season than Borussia Dortmund and Borussia Dortmund has conceded more than PSG this season.
- PSG has won more games in total this season and has lost fewer games when compared to Borussia Dortmund.
- PSG and Borussia Dortmund has both won 12 home games this season  and PSG has lost fewer homes games when compared to dortmund.
- PSG has more away wins and fewer away losses when compared to Borussia Dortmund in all competitions this season.

#### Analysis on total Head to Head matches between Borussia Dortmund and PSG 

- Both teams have met 4 times before and both teams have won once, lost once and drawn 2 times.

### Insights from the Analysis of the teams in the finals -- Borussia Dortmund vs Real Madrid

- Real Madrid has higher average goals scored per game in both current season and historically when compared to Borussia Dortmund in the champions league competition.
- Borussia Dortmund has the higher average goals conceded per game, both in current season and historically when compared to Real Madrid in champions league.

<img src="Images and Screenshots/Screenshot 2024-08-27 211639.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211705.png" alt="Champions League Trophy" width="100%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211842.png" alt="Champions League Trophy" width="100%" height="500" />

- Real madrid has won 7/10 games and Borussia Dortmund has won 5/10 games in this UCL season. Real madrid has not lost a single game whereas Borussia Dortmund have lost 2 games. Both Real madrid and Borussia Dortmund Have drawn 3 times in the current UCL season.

<img src="Images and Screenshots/Screenshot 2024-08-27 211724.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211906.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211749.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211811.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 211927.png" alt="Champions League Trophy" width="80%" height="500" />
<img src="Images and Screenshots/Screenshot 2024-08-27 212013.png" alt="Champions League Trophy" width="45%" height="300" />

# Model Selection

Several models were evaluated, including Logistic Regression, XGBoost, and Random Forest. The Random Forest model was selected due to its ability to manage complex feature interactions, its superior prediction accuracy and provide interpretable results.

# Prediction Process

### Semifinals -- Bayern Munich vs Real Madrid -- Winner Prediction 
1st Leg of the semifinals - 01/05/2024 -- Bayern's home match

2nd Leg of the semifinals - 09/05/2024 -- Real's home match
#### Predictions for this semifinals were made on 30/04/2024

- Data from different excel sheets were oraganised and combined to make the predictive model efficient.

<img src="Images and Screenshots/Screenshot 2024-08-26 213225.png" alt="Champions League Trophy" width="100%" height="250" />

- Used feature engineering to create key factors for the predictive model.

<img src="Images and Screenshots/Screenshot 2024-08-26 213253.png" alt="Champions League Trophy" width="100%" height="500" />

- Imported libraries and models needed for the predictions

<img src="Images and Screenshots/Screenshot 2024-08-27 133633.png" alt="Champions League Trophy" width="100%" height="400" />

- Selected the columns with key factors for the predictive model

<img src="Images and Screenshots/Screenshot 2024-08-27 134054.png" alt="Champions League Trophy" width="100%" height="200" />

- Trained and tested the model for accuracy and precision.

<img src="Images and Screenshots/Screenshot 2024-08-27 134126.png" alt="Champions League Trophy" width="100%" height="800" />
<img src="Images and Screenshots/Screenshot 2024-08-27 134140.png" alt="Champions League Trophy" width="45%" height="150" />

- Predicted the results of both the 1st leg and the 2nd leg of the semifinals between Bayern Munich and Real Madrid

<img src="Images and Screenshots/Screenshot 2024-08-27 134231.png" alt="Champions League Trophy" width="100%" height="800" />

### Semifinals -- Borussia Dortmund vs Paris Saint-Germain -- Winner Prediction 
1st Leg of the semifinals - 02/05/2024 -- Dortmund's home match

2nd Leg of the semifinals - 08/05/2024 -- PSG's home match
#### Predictions for this semifinals were made on 30/04/2024

- Performances by both the teams from the previous season was also collected and used

- Data from different excel sheets were oraganised and combined to make the predictive model efficient.

<img src="Images and Screenshots/Screenshot 2024-08-28 145623.png" alt="Champions League Trophy" width="100%" height="200" />

- Used feature engineering to create key factors for the predictive model.

<img src="Images and Screenshots/Screenshot 2024-08-28 145644.png" alt="Champions League Trophy" width="100%" height="500" />

- Selected the columns with key factors for the predictive model

<img src="Images and Screenshots/Screenshot 2024-08-28 145716.png" alt="Champions League Trophy" width="100%" height="170" />

- Trained and tested the model for accuracy and precision.

<img src="Images and Screenshots/Screenshot 2024-08-28 145738.png" alt="Champions League Trophy" width="100%" height="800" />
<img src="Images and Screenshots/Screenshot 2024-08-28 145750.png" alt="Champions League Trophy" width="45%" height="150" />

- Predicted the results of both the 1st leg and the 2nd leg of the semifinals between Borussia Dortmund and Paris Saint-Germain

<img src="Images and Screenshots/Screenshot 2024-08-28 145805.png" alt="Champions League Trophy" width="100%" height="800" />

### Finals -- Borussia Dortmund vs Real Madrid -- Winner Prediction (01/06/2024) -- London Stadium

#### Predictions for this finals were made on 31/05/2024

- Data from different excel sheets were oraganised and combined to make the predictive model efficient.

<img src="Images and Screenshots/Screenshot 2024-08-28 145901.png" alt="Champions League Trophy" width="100%" height="200" />

- Used feature engineering to create key factors for the predictive model.

<img src="Images and Screenshots/Screenshot 2024-08-28 145916.png" alt="Champions League Trophy" width="100%" height="500" />

- Selected the columns with key factors for the predictive model

<img src="Images and Screenshots/Screenshot 2024-08-28 145937.png" alt="Champions League Trophy" width="100%" height="170" />

- Trained and tested the model for accuracy and precision.

<img src="Images and Screenshots/Screenshot 2024-08-28 145956.png" alt="Champions League Trophy" width="100%" height="800" />
<img src="Images and Screenshots/Screenshot 2024-08-28 150009.png" alt="Champions League Trophy" width="45%" height="150" />

- Predicted the result of the finals between Borussia Dortmund and Real Madrid

<img src="Images and Screenshots/Screenshot 2024-08-28 150027.png" alt="Champions League Trophy" width="100%" height="800" />

# Prediction Results

### Semifinals -- Bayern Munich vs Real Madrid

- The model predicts that the likely winner of the 1st leg semi finals between Bayern Munich and Real Madrid in Bayern's home stadium is -- "BAYERN MUNICH" (2-1)

- The model predicts that the likely winner of the 2nd leg semi finals between Bayern Munich and Real Madrid in Real's home stadium is -- "REAL MADRID" (0-2)

#### The model predicts that Real Madrid is likely to win the semifinals with an aggregate of (3-2) and goes to the finals.

<img src="Images and Screenshots/Screenshot 2024-08-27 134251.png" alt="Champions League Trophy" width="100%" height="270" />

### Semifinals -- Borussia Dortmund vs Paris Saint-Germain

- The model predicts that the likely winner of the 1st leg semi finals between Borussia Dortmund and Paris Saint-Germain in Dortmund's home stadium is -- "BORUSSIA DORTMUND" (2-1)

- The model predicts that the likely winner of the 2nd leg semi finals between Borussia Dortmund and Paris Saint-Germain in PSG's home stadium is -- "PARIS SAINT-GERMAIN" (1-3)

#### The model predicts that Paris Saint-Germain is likely to win the semifinals with an aggregate of (4-3) and goes to the finals.

<img src="Images and Screenshots/Screenshot 2024-08-28 145823.png" alt="Champions League Trophy" width="100%" height="350" />

#### This prediction for the semifinals between Borussia Dortmund vs Paris Saint-Germain was made on 30/04/2024, before the actual match. After both the legs of the semi finals which were held on 01/05/2024 and 08/05/2024, Borussia dortmund wins against PSG in the semi finals with an aggregate of (2-0) thus making the above prediction wrong. The finals prediction was made on 31/05/2024, ie after the semi finals and before the finals that was held on 01/06/2024. Since I knew the results of the semi finals before making the prediction of the finals I was able to do the analysis and prediction on Real Madrid vs Borussia Dortmund.

### Finals -- Borussia Dortmund vs Real Madrid

- The model predicts that the likely winner of the  finals between Borussia Dortmund and Real Madrid is -- "Real Madrid" (1-3)

#### The model predicts that Real Madrid is likely to win the the champions league 2024 finals with a score of (1-3).

<img src="Images and Screenshots/Screenshot 2024-08-28 150040.png" alt="Champions League Trophy" width="100%" height="200" />

# Champions League 2024 Winner -- "FC REAL MADRID..."

# Conclusion

This project illustrates the potential of data-driven predictions in sports, specifically in high-stakes matches like the UEFA Champions League semifinals and finals. While the model offers statistically grounded predictions, football's unpredictable nature means that upsets are always possible. Future enhancements could include real-time updates and the integration of more contextual factors like weather conditions, player form, injuries or in-game momentum shifts.

# Acknowledgments

Thanks to [UEFA.com](#), wikipedia and official sites of Real Madrid, Bayern Munich, Borussia Dortmund and Paris Saint-Germain for the data used in this project.
