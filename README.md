# IPL 2026: Ball-by-Ball Dataset (All Matches)

This repository contains the complete ball-by-ball dataset of all 74 matches played during the Indian Premier League (IPL) 2026 season.

The dataset includes a single combined file of all deliveries across all matches for easy bulk analysis, as well as separate CSV files for each individual match organized in the `matches` folder.

## Repository Structure

- `ipl_2026_ball_by_ball.csv`: Combined ball-by-ball data for all 74 matches of IPL 2026 (Priority file).
- `matches/`: A folder containing separate CSV files for each match (e.g., `match_01_srh_vs_rcb.csv` through `match_74_gt_vs_rcb_final.csv`).

## Dataset Columns

The CSV files include the following columns for every delivery:
* **Innings**: Innings number (1 or 2).
* **Over**: The over number (0 to 19).
* **Ball**: The ball number within the over.
* **Bowler**: The bowler delivering the ball.
* **Batter**: The batsman facing the delivery.
* **Non-Striker**: The batsman at the non-striker's end.
* **Runs_Off_Bat**: Runs scored off the bat.
* **Extras**: Extra runs conceded (wides, no-balls, legbyes, byes, etc.).
* **Extra_Type**: Type of extra, if applicable.
* **Wicket_Type**: How the batsman was dismissed (caught, bowled, stumped, lbw, run out, etc.).
* **Player_Dismissed**: Name of the batsman dismissed.
* **Fielder**: Name of the fielder involved in the dismissal.
* **Total_Team_Runs**: Cumulative team score after the delivery.
* **Wickets_Lost**: Cumulative wickets lost after the delivery.
