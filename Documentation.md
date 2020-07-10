## Motives and Background
I enthusiastic football news and I always pay attention to the standings especially in the five most popular leagues in continental Europe such as the Bundesliga, Premier League, Serie A, Primera Division and ligue 1. In the beginning I was very lazy to access any official website from the five most popular leagues in Europe one by one. Because of that I got the idea to create a rest api program to access the data base from outside so that I could easily get information from each of the five most popular soccer leagues on the European continent.

## Project Duration
I made this rest api program in 3 days because I learned about fire rest first and after that I started to manage and develop the data through the program that I created.

## The Code's Structure
The EuropeanSoccerLeagueStandingsAPI.ipynb is the main class or the starting point

## Class and Function Interface

**File :** EuropeanSoccerLeagueStandingsAPI.ipynb

Function name | Access level | Parameter | return
--- | --- | --- | ---
show_svg | Public | url : str | display image
standings | Public | id : str, connection:connection, headers:headers | response:response
scorers | Public | id : int, connection:connection, headers:headers | response:response
teams | Public | id : int, connection:connection, headers:headers | response:response
standings_league_info | public | league : str | print(standings info in specific league)
top_3_teams_in_all_league | public | none | print(top 3 teams in each league)
team_info | public | club : str | print(team standings info)
get_top_scores_in_league | public | league : str | print(top scorers in specific league)
get_top_3_scores_in_all_league | public | none | print(Get top 3 scorers in each league)
 
## Statistic
I wrote 182 line of codes by myself in EuropeanSoccerLeagueStandingsAPI.ipynb file.
