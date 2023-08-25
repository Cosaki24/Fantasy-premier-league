# Fantasy Premier League with Python

Hello, I'm currently playing the famous Fantasy Premier League(FPL)

As I am learning Data Science, I want to put it into practice, so that
I can use it to find/get most out of my premier league fantasy team.
As we all know, bias is common towards choosing a squad, or we might hold on to
players without returns. So using various python modules, we will create a fantasy
team so that we can get as many points as we can. Let's go.

To select the squad, it utilizes linear programming model with the following objectives function and constraints:

Objective functions:
-Maximize Total points
-Maximize ICT index
-Minimize cost.

Constraints:
-Max 15 players
-Max 3 players per team
-2 Goal Keepers
-5 Defenders
-5 Midfielders
-3 Attackers
-Maximum of 100million to purchase squad.(1000 credits in code)

The player data is available from the [official fantasy premier league api](https://fantasy.premierleague.com/api/)
