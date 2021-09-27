## Project Name:

 Discount Fighters
 
## Author:

 Neag Mircea
 
## Description:

 Game prototype to demonstrate the use of AI/Agents in games for a better user experience/challenge, game art and 
some mechanics are inspired from once popular flash game, Chaos Faction 2.
 
## Type of Agents/AI:

 __[Puchbag]__
 
 Description: "Empty" brain used for testing.
 
 __[Randumb]__
 
 Descripton: Actions are taken randomly.
 
 __[Randsmart]__
 
 Description: Has three float numbers each representing a strategy (aggressive, defensive, greedy) 
whose initial values were determined via a genetic algorithm. The winning strategy is 
the one with highest random(0, initial_strategy_value).

 __[Hardcoded]__
 
 Description: This agent takes data from the game environemnt and passes it through different if statements
(has_weapon, health_value > x, in_danger) to determine best action. Hence the name "hardcoded".

 __[Utility Agent]__
 Description: Like above this agent takes data from its environment but uses that information in response curves
to determine the best actions(similar to fuzzy logic).

 The algorithm of an utility agent is divided in:

[Consideratons]
 The information to consider transalted in response curves;

[Decisions]
 The decision to take, constains a list of considerations;

[Selector] 
 The logic to select the best decision/action, it can be 
highest value, weighted random etc;

 This agent achieved 100% winrate against the others 
and even beat human players.
 
More about [utility agents](https://www.gdcvault.com/play/1021848/Building-a-Better-Centaur-AI)
 
## Operating systems:
 PC, any OS
 
## Technologies used:

 Unity Engine, C#
 

 