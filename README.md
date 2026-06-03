# IPL 2026 Ball by Ball Dataset (All Matches)

This repository contains the complete ball-by-ball dataset for all 74 matches played during the 2026 Indian Premier League season. It includes a combined dataset for large-scale analysis and individual files for each match.

The season ended on May 31, 2026, with Royal Challengers Bengaluru winning their second consecutive title by defeating Gujarat Titans by five wickets in the final at Ahmedabad.

## Directory Structure

* `ipl_2026_ball_by_ball.csv`: The combined ball-by-ball data of all 74 matches in a single file. This is the primary file for analyzing the entire season at once.
* `matches/`: A folder containing 74 separate CSV files. Each file covers a single match, from the opening game to the final. The files are named sequentially (e.g., `match_01_srh_vs_rcb.csv` through `match_74_gt_vs_rcb_final.csv`).

## Data Columns

Every CSV file in this dataset uses the following columns for each delivery:

* Innings: 1 for the team batting first, 2 for the team batting second.
* Over: The over number, from 0 to 19.
* Ball: The delivery number within that over.
* Bowler: The name of the bowler.
* Batter: The batter facing the delivery.
* Non-Striker: The batter at the non-striker's end.
* Runs_Off_Bat: Runs scored directly from the bat.
* Extras: Extra runs conceded.
* Extra_Type: Type of extra (wides, no-balls, legbyes, or byes), if applicable.
* Wicket_Type: How the batter was dismissed (caught, bowled, stumped, lbw, run out, etc.), if a wicket fell.
* Player_Dismissed: The name of the dismissed batter.
* Fielder: The name of any fielder involved in the dismissal.
* Total_Team_Runs: The cumulative team score after the delivery.
* Wickets_Lost: The cumulative number of wickets lost after the delivery.
