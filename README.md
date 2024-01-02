# PigRoll Python Challenge

## Project description

Pig Game is a multiplayer turn-based dice game where each player accumulates a total score while strategically deciding when to stop rolling the dice. Players can roll a die and add the obtained score to their turn total; however, rolling a 1 resets the turn total to zero.

The game begins by prompting the user to input the number of players (a minimum of 2) and initializes a loop to ensure valid input. Players take turns rolling the die, deciding whether to continue rolling or stop, and accumulating scores. The game dynamically checks for a winning condition, declaring the first player to reach a specified maximum score (e.g., 50) as the winner.


## Key Features:

Random Die Rolling: Utilizes Python's random module to simulate the rolling of a six-sided die.

User Input Handling: Implements robust input validation to ensure accurate and meaningful user interactions.

Multi-Player Support: Allows a customizable number of players to participate, with a minimum of two.

Turn-Based Gameplay: Utilizes loops to simulate turn-based gameplay, where each player takes turns rolling the dice and making strategic decisions.

Winning Condition: Dynamically checks for a winning condition and declares the player with the highest score as the winner.
