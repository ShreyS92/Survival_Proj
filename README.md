## Prediction of Survival of teams that are promoted to the Premier League
Every season, three teams are promoted to the first division of the English Footballing Pyramid, the Premier League. But due the competitiveness of the league, these three teams are also considered to be the favorites to be relegated in the first season they reach the league, paving ways for new teams.<br /> <br />
Using some factors that are present, we would like to create a model that can predict whether a recently promoted team can survive, or will they get relegated the same season they came up.<br /> <br />
# Dataset <br />
The Dataset contains two files. File 1, Promoted_Teams, which has the main data that we will use to make the Logistic Model for Regression, and Total_Exp, which has the total money spent each season. The use for the second file is to improve the Money_Spent factor in the original dataset. This is because of implicit trends present in the variable Money_Spent present in the Promoted_Teams file. <br /><br />
#Note - <br />
In the original dataset, the column 'Name' is actually written as 'Name '.  