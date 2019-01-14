# THE PIG DICE GAME
#### The Pig Dice WebApp Game, 14/01/19

#### By **Simpenzwe Anais**

## Description
Players throw a dice and scores as many points as the total shown on the dice providing the dice doesn’t roll a 1. The player may continue rolling and accumulating points (but risk rolling a 1) or end his turn. If the player rolls a 1 his turn is over, he loses all points he accumulated that turn, and he passes the die to the next player. Play passes from player to player until a winner is determined. The first player to accumulate 100 or more points wins the game.

## Technologies Used
- HTML
- CSS
- Bootstrap
- JavaScript
- jQuery
- Git
## Setup
Run this link to play the game:

## BDD Specifications
| Behavior                          |  Input Example |  Output  Example|
|----------                         |:-------------: |------:          |
| Player 1 and Player 2 input names, and click start |  Player 1:Ana / Player 2: simp / Click START    | Then starts the game |
|  Player 1 clicks Roll |  Click roll    |  Number is generated, Dice is displayed  |
|If Player rolls any number other than 1, roll is added to round total   | Roll = 5     |  Round Total =5    |
|If Player1 rolls 1, no score is added and round for Player 2  |  Roll = 1    |  Round Total = 0, Score = 0,  Player2 plays    |
|If Player1 clicks Hold, round total is added to his score and it's Player2 Turn | Click Hold     |  Round Total = 5, Score = 5, Player2 plays    |
| When a player's total score is 10 or more, game is over and winner alert shows  |  Player 1 score = 15	    | Newton WINS (SweetAlert)    |
#### Support and Contact
If you ever have a question about the Quiz-Board website feel free to contact me at:
* Phone Number:+250783711066 to call me or
* Email:anaissimpenzwe@gmail.com to send me an Email
### Licence
MIT Licence
© 2018 Simpenzwe Anais All Rights Reserved