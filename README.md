## Project Name:

 Discount Fighters
 
## Author:

 Neag Mircea
 
## Description:

 Game prototype to demonstrate the use of AI/Agents in games for a better user experience/challenge, game art and 
some mechanics are inspired from the once popular flash game, Chaos Faction 2.
 
## Type of Agents/AI:

 __[Puchbag]__
 
 "Empty" brain used for testing.
 
 __[Randumb]__
 
 Actions are taken randomly.
 
 __[Randsmart]__
 
 Has three float numbers each representing a strategy (aggressive, defensive, greedy) 
whose initial values were determined via a genetic algorithm. The winning strategy is 
the one with highest random(0, initial_strategy_value).

 __[Hardcoded]__
 
 This agent takes data from the game environment and passes it through different if statements
(has_weapon, health_value > x, in_danger) to determine the best action. Hence the name "hardcoded".

 __[Utility Agent]__
 
 Like above this agent takes data from its environment, but uses that information in response curves
to determine the best actions(similar to fuzzy logic).

 The algorithm of an utility agent is divided into:

[Considerations]
 The information to consider translated in response curves;

[Decisions]
 The decision to take, contains a list of considerations;

[Selector] 
 The logic to select the best decision/action, it can be 
highest value, weighted random etc;

 This agent achieved 100% win rate against the others 
and even beat human players.
 
More about [utility agents](https://www.gdcvault.com/play/1021848/Building-a-Better-Centaur-AI)
 
## Operating systems:
 PC, any OS
 
## Technologies used:

 Unity Engine, C#
 
## Screenshots:
 
 * Start Menu:
 
 ![alt text](https://github.com/NeagMircea/Discount-Fighters/blob/main/screenshots/start_menu.png "Start Menu")
 
 * Character Select:
 
 ![alt text](https://github.com/NeagMircea/Discount-Fighters/blob/main/screenshots/character_select.png "Character Select")
  
 * Map Select:
 
 ![alt text](https://github.com/NeagMircea/Discount-Fighters/blob/main/screenshots/map_select.png "Map Select")
 
 * Game Shot:
 
 ![alt text](https://github.com/NeagMircea/Discount-Fighters/blob/main/screenshots/game_shot.png "Game Shot")
 

 