## How do Salary Caps Impact Professional Sport? README

**How to View:** The main report is in the jupyter notebook 'How do Salary Caps Impact Professional Sport. If you want to look at the methods used to collect the data, those are in the 'Data Collection and Munging' jupyter notebook. 


**Data**: The data used for the project is stored in FootballData.sqlite. Some Raw data which I got from websites and put into csv documents is in the raw_data folder. There is a requests cache in the file 'coll_cache.sqlite'.

**List of tables:**

-first_div_winners: Table of winners from 1892-1992

-pl_winners: Table of winners from 1992-2017

-full_EPL_winners: first_div_winners and pl_winners

-titles: Table of the number of First Division Clubs who have won and how many times. Also includes runners-up

-EPLseason_results_2015: Final Premier League Table for 2015-2016

-EPLmatches_2015: Matches in a Matrix by club, home games are rows, column games are away

-lc_rank: Leicester City's Rank in English football through time

-pl_season_stats_(INTEGER 0-15): Overall stats by club for the 2000-2016 seasons. Some not included for 2000-2006.

-NAME_2015_stats: Table of a club with name = NAME by player for the 2015-16 season formatted lowercase with spaces as '_' e.g. west_bromwich-albion_2015_stats is the season stats by player for 2015-16

-NBA_winners: Table of winners in the NBA

-MLS_winners: Table of winners in the MLS

-NFL_winners: Table of winners in the NFL superbowl era

-MLB_winners: Table of winners in the MLB