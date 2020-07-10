# Europan-Soccer-League-Standings-API
![Python-Versions](https://img.shields.io/badge/python-3.7-blue?style=flat-square)

## Purpose
This is a project of the European Soccer League Standings API. The purpose of the project was to get information about the standings in each of the most popular leagues on the European continent. This project uses the API as its database, the reason for using the API here is to make this project more modular.

## Run requirements:
* Jupyter Notebook

## How to run this program:
There are five functions that can be used to show the desired data. 
1. First, ```standings_league_info(league)``` function. We can run this functions within input a popular league name in Europe such as `Bundesliga`, `Premier League`, `Serie A`, `Primera Division` or `Ligue 1`. A league name is a parameter for the function to get the standings league info at input league. This function will be return a show of the standings info in specific league.

2. Second, ```top_3_teams_in_all_league()``` function. We can run this function to get top 3 teams in each league. This function will be return a show of the top 3 teams in each league.

3. Third, ```team_info(club)``` function. We can run this function with the parameter is the name of the club at the five popular soccer leagues in the Europe such as `chelsea`. This function will be return a show of the team standings info.

4. Fourth, ```get_top_scores_in_league(league)``` function. We can run this functions within input a popular league name in Europe such as `Bundesliga`, `Premier League`, `Serie A`, `Primera Division` or `Ligue 1`. A league name is a parameter for the function to get the top scorer at input league. This function will be return a show of top scorers in specific league.

5. Five, ```get_top_3_scores_in_all_league()``` function. We can run this function to get top 3 scorers in each league. This function will be return a show of the top 3 scorers in each league.

## The sources that I take to retrieve data are:
* [Football data api](https://www.football-data.org/)

## Author
* By Ari Purnama Aji (aripurnamaaji78@gmail.com)
* My github : [AriPurnamaAji](https://github.com/AriPurnamaAji)

## License
Copyright (c) by Ari Purnama Aji
