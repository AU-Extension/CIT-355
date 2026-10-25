# Biscayne Bay Sports Group data

All data is fictional and created for CIT 355 at Atlantis University. Names of people, clubs, and businesses are invented. Download any file and open it in Excel or Google Sheets.

## basketball_games.csv

Biscayne Bay Breakers, 40 games of the 2026-27 season. Home games include attendance, average ticket price, and the promotion used. (40 rows)

Columns: `game_id`, `date`, `day_of_week`, `tipoff`, `opponent`, `home_away`, `rivalry`, `result`, `points_for`, `points_against`, `fg_pct`, `three_pt_pct`, `rebounds`, `assists`, `turnovers`, `promotion`, `attendance`, `avg_ticket_price`

## basketball_games_raw.csv

The same games before cleaning, with deliberate errors. Used in Week 2. (41 rows)

Columns: `game_id`, `date`, `day_of_week`, `tipoff`, `opponent`, `home_away`, `rivalry`, `result`, `points_for`, `points_against`, `fg_pct`, `three_pt_pct`, `rebounds`, `assists`, `turnovers`, `promotion`, `attendance`, `avg_ticket_price`

## basketball_players.csv

The current Breakers roster with per-game statistics and salaries. (13 rows)

Columns: `player_id`, `name`, `position`, `age`, `games_played`, `minutes_per_game`, `points_per_game`, `rebounds_per_game`, `assists_per_game`, `fg_pct`, `three_pt_pct`, `turnovers_per_game`, `annual_salary`, `contract_end`

## basketball_scouting_targets.csv

24 basketball players the team could sign, with per-36-minute statistics, injury history, and salary ask. (24 rows)

Columns: `target_id`, `name`, `position`, `age`, `current_league`, `games_played`, `points_per36`, `rebounds_per36`, `assists_per36`, `fg_pct`, `three_pt_pct`, `turnovers_per36`, `injury_games_missed_last_2yrs`, `salary_ask`

## fan_comments.csv

240 fan comments from social media and the team app, in English and Spanish, without sentiment labels. (240 rows)

Columns: `comment_id`, `date`, `team`, `platform`, `comment`

## fans.csv

1,200 fans in the club database: age, home area, team preference, attendance, spending, app use, email engagement, and season ticket renewal. (1200 rows)

Columns: `fan_id`, `age`, `home_area`, `team_preference`, `games_attended_last_season`, `season_ticket_holder`, `merch_spend`, `concessions_spend`, `uses_team_app`, `email_open_rate`, `years_as_fan`, `renewed_season_ticket`

## soccer_matches.csv

Biscayne Bay FC, 34 league matches of the 2026 season. Home matches include attendance, average ticket price, and the promotion used. (34 rows)

Columns: `match_id`, `date`, `day_of_week`, `kickoff`, `opponent`, `home_away`, `rivalry`, `result`, `goals_for`, `goals_against`, `xg_for`, `xg_against`, `possession_pct`, `shots`, `shots_against`, `weather`, `promotion`, `attendance`, `avg_ticket_price`

## soccer_matches_raw.csv

The same matches before cleaning, with deliberate errors (duplicate row, mixed date formats, impossible values, text in number columns). Used in Week 2. (35 rows)

Columns: `match_id`, `date`, `day_of_week`, `kickoff`, `opponent`, `home_away`, `rivalry`, `result`, `goals_for`, `goals_against`, `xg_for`, `xg_against`, `possession_pct`, `shots`, `shots_against`, `weather`, `promotion`, `attendance`, `avg_ticket_price`

## soccer_players.csv

The current Biscayne Bay FC squad with season totals and salaries. (26 rows)

Columns: `player_id`, `name`, `position`, `age`, `minutes`, `goals`, `assists`, `xg`, `pass_completion_pct`, `tackles`, `interceptions`, `saves`, `annual_salary`, `contract_end`

## soccer_scouting_targets.csv

30 soccer players the club could sign, with per-90-minute statistics, injury history, transfer fee, and salary ask. (30 rows)

Columns: `target_id`, `name`, `position`, `age`, `current_league`, `minutes`, `goals_per90`, `assists_per90`, `xg_per90`, `key_passes_per90`, `tackles_per90`, `pass_completion_pct`, `injury_days_last_2yrs`, `transfer_fee`, `salary_ask`

## sponsors.csv

12 sponsors with annual fee, media impressions, events, leads, attributed sales, and renewal status. (12 rows)

Columns: `sponsor`, `category`, `team`, `annual_fee`, `media_impressions`, `activation_events`, `leads_generated`, `attributed_sales`, `renewal_status`

## ticket_sales.csv

Tickets sold, price, and revenue for every home game, by seating section, for both teams. (152 rows)

Columns: `team`, `game_id`, `date`, `opponent`, `section`, `capacity`, `price`, `tickets_sold`, `revenue`

## workloads.csv

Weekly training load, minutes, effort rating, sleep, and injuries for 26 players over 12 weeks. (312 rows)

Columns: `player_id`, `name`, `sport`, `position`, `week`, `weekly_load`, `minutes_played`, `avg_session_rpe`, `sleep_hours_avg`, `injured_this_week`

