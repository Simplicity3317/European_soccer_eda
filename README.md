# Exploratory Data Analysis on European Soccer League.
## by Ismaheel Bello

## Dataset
The dataset used for this project can be downloaded <a href='https://www.kaggle.com/datasets/hugomathien/soccer?select=database.sqlite'>here.</a>

## Dataset Description
The Soccer dataset consist of 7 different tables which are:

1. Country
2.League
3. Match
4. Player
5. Player attributes
6. Team
7. Team Attributes
In the Country table, we have the Country ID and the Country Name. 
In the League table, we have columns like Country_id and League_Name. 
In the Match Table, we have several details of each Match played, the ones we'll be making use of in this Analysis are Season, Home_team_goal, Away_team_goal.
In the Player Table also consist of different columns,but the one's relevant for the purpose of this project are Player_api_id, height and weight.
We also have the Player Attributes tables, which cotains information about the attributes of the Players but for this project we'll be extracting the Player Attributes Column and The Player Potential Column. 
The team table also consist of several columns and the one's we'll be extracting for this project work are Team_api_id, Team_Long_Name.
The team attributes tables also contains several details about the Team, but for this project, we're not extracting any details from the table.

## Summary of findings

### Research Question 1:
From the analysis that we did in our reseach question 1, we find out that the most goals was scored during the 2015/2016 season of the European League, a total number of 9162 goals was scored, we also find out that it was during the Spain LIGA BBVA league that the highest number goal was scored in that Season, the numbers of goal scored was 1043.

### Research Question 2:
According to the analysis we did in research question two, we were able to get the total number of matches that was played in each League from 2008/2009 season to 2015/2016 season, and from the anaysis the highest number of matches was played in English Premier League, France Ligue 1 and Spain LIGA BBVA with a number of 3040 matches each,followed by Italy Serie A league with 3017 number of matches,followed by Germany 1. Bundesliga and Netherlands Eredivisie League with a number of 2448 matches each, followed by Portugal Liga ZON Sagres with 2052 number of matches, followed by Poland Ekstraklasa league with 1920 number of matches, followed by Scotland Premier League with 1824 number of matches, followed by Belgium Jupiler League with 1728 number of matches,and then followed by Switzerland Super League with 1422 number of matches.

### Research Question 3:
According to the analysis for research question 3, we noticed that Danilo is most rated with 482.72 points, followed by Paulinho with 409.76 points, followed by Ricardo with 348.81 points, followed by Fernado with 301.38 points, followed by Adriano with 290.66 points, followed by Felipe with 290.40 points, followed by Douglas with 283 points, followed by Rafael with 274.50 points , then followed by Joao Pedro with 258.96 points.

### Research Question 4:
According to the correlation we carried in research question 4, we got Pearson Correlation Coefficient value of ~0.8, this simply implies that there is a strong Positive Linear Correlation between Player Overall average rating and their Potentials. Also we carried out a Statistical Test to comfirm if they're statistically Significant, with a 0.05 level of Significance, and from our result we got a pvalue of 0.00, these shows that our pvalue is very small, and decision rule states that we're to reject the null hypothesis if the pvalue < level of siginicance(0.05 in this case), Since our pvalue(0.00) is less than 0.05, we therefore reject the null hypothesis and Conclude that the correlation between Player Overall average rating and  Player Average Potential  are Statistically Significant, and thus there is a Significant relationship between them.

### Research Question 5:
According to the Pearson Correlation coefficient value that we got which is ~0.8 , it implies that there is a Strong Positive Linear Association between Player Average Weight and Player Average Height. We need to Statistically prove this as well, so we carried out a Statistical test with 0.05 level of Significance, and from the resul obtained, our pvalue is 0.00, and since the decision rule states that we are to reject the Null hypothesis if the pvalue is less than the Level of Significance, thus we obtained pvalue of 0.00, and 0.00 < 0.05, we therefore reject the null hypothesis and conclude that the correlation coefficient value (0.766) is statistically significant,and the linear relationship is extremely strong, therefore there is Statistical Relationship between Player Average Weight and Player Average height.