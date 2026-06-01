# IPL 2026 Final: Ball-by-Ball Dataset

This repository contains the complete ball-by-ball dataset of the IPL 2026 final played on May 31, 2026, at the Narendra Modi Stadium in Ahmedabad. 

The match saw Royal Challengers Bengaluru (RCB) win their second consecutive title by defeating Gujarat Titans (GT) by five wickets.

## Match Summary

### Gujarat Titans Innings
Gujarat Titans chose to bat first but struggled to construct partnerships on a slow pitch. RCB's bowlers exploited the conditions early, keeping the scoring rate down. Shubman Gill fell to Josh Hazlewood for 10, and Sai Sudharsan followed soon after, caught off Bhuvneshwar Kumar for 12. 

Nishant Sindhu (20 off 18) and Jos Buttler (19 off 23) attempted a recovery but could not get going. Rasikh Salam broke the stand by dismissing Sindhu, and Krunal Pandya got Buttler stumped. Arshad Khan played a quick cameo of 15 from 6 balls before falling to Hazlewood. 

Washington Sundar was the only batsman who looked comfortable, scoring an unbeaten 50 off 37 balls. His effort pushed the Titans to a total of 155 for 8. Rasikh Salam finished with 3 for 27, while Bhuvneshwar Kumar and Josh Hazlewood took two wickets each.

### Royal Challengers Bengaluru Innings
RCB chased the target of 156 in 18 overs, finishing at 161 for 5. Venkatesh Iyer gave them a quick start with 32 off 16 balls before Mohammed Siraj dismissed him. Devdutt Padikkal fell cheap to Kagiso Rabada for 1. 

Rashid Khan struck twice in quick succession, dismissing Rajat Patidar for 15 and Krunal Pandya for 1. This put RCB under pressure at 132 for 5. 

Virat Kohli anchored the innings. He played aggressively, reaching his half-century in 25 balls, his fastest in IPL history. Tim David supported him with 24 off 14 balls. Kohli finished the match with a six off Kagiso Rabada in the 18th over, ending unbeaten on 75 off 42 balls.

## Dataset Structure

The CSV file includes the following columns for every delivery of the match:
* **Innings**: 1 for GT, 2 for RCB.
* **Over**: The over number (0 to 19).
* **Ball**: The ball number within the over.
* **Bowler**: The bowler delivering the ball.
* **Batter**: The batsman facing the delivery.
* **Non-Striker**: The batsman at the non-striker's end.
* **Runs_Off_Bat**: Runs scored from the bat.
* **Extras**: Extra runs conceded (wides, no-balls, legbyes, byes).
* **Extra_Type**: Type of extra, if applicable.
* **Wicket_Type**: How the batsman was dismissed (caught, bowled, stumped, lbw, caught and bowled).
* **Player_Dismissed**: Name of the batsman dismissed.
* **Fielder**: Name of the fielder involved in the dismissal.
* **Total_Team_Runs**: Cumulative team score after the delivery.
* **Wickets_Lost**: Cumulative wickets lost after the delivery.
