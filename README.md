# LoL-Stats

League of Legends is a team-based strategy game where two teams of five champions face off to destroy the other's base. With over 140 champions to choose from, how can we improve our chances of winning based on statistics and champion win rates.

## Getting Started
By accessing League of Legend's developers API, we can access the data of matches that are already played. 
https://developer.riotgames.com/apis

## Cleaning of Data
There are multiple steps to take here to clean the data.
1. First we have to get a user's account history of matches played from:
https://developer.riotgames.com/apis#match-v4/GET_getMatchlist
-INSERT PICTURE OF EXAMPLE-
I want to then save all records of "gameID" so I can then query it into 
https://developer.riotgames.com/apis#match-v4/GET_getMatch
which will return details about the match. 
-INSERT PICTURE OF MATCH DETAILS-
2. Based off the information we get from matchs, store the details into json/database?
3. Create a panda's dataframe and then create data visualzation graphs with the data.

## Features?
1. Show a player's match history up to past 20 games. Currently you can only see your past 20 games you have played.
2. Show a player's champion statistics from highest to lowest

## Storage plans

## Expected transformations

## Expected visualization tool and publishing
