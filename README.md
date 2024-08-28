# End-to-End-ML-with-Scotium-Talent-Hunt
# Business Problem
Predicting the class (average, highlighted) of players based on the ratings given to their characteristics by scouts.

# About Dataset
The dataset consists of evaluations made by scouts on players observed during matches. It includes information on the rated characteristics and scores of the players evaluated by the scouts.

## scoutium_attributes.csv:

8 Variables
10,730 Observations
Variables:

task_response_id: A set of evaluations for all players in a team by a scout during a match.

match_id: ID of the respective match.

evaluator_id: ID of the evaluator (scout).

player_id: ID of the respective player.

position_id: ID of the position played by the player in that match (1: Goalkeeper, 2: Center-back, 3: Right-back, 4: Left-back, 5: Defensive Midfielder, 6: Central Midfielder, 7: Right Winger, 8: Left Winger, 9: 
Attacking Midfielder, 10: Forward).

analysis_id: A set of characteristic evaluations of a player by a scout during a match.

attribute_id: ID of each characteristic evaluated for the players.

attribute_value: The score given by a scout to a player’s characteristic.

## scoutium_potential_labels.csv:

5 Variables
322 Observations
Variables:

task_response_id: A set of evaluations for all players in a team by a scout during a match.

match_id: ID of the respective match.

evaluator_id: ID of the evaluator (scout).

player_id: ID of the respective player.

potential_label: The final decision label of a scout on a player during a match (target variable).
