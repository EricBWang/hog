# hog
Hog is a project that creates a dice game simulator with special rules by using higher order functions and control statements. In Hog, two players alternate turns trying to be the first to end a turn with at least 100 total points. On each turn, the current player chooses some number of dice to roll, up to 10. That player's score for the turn is the sum of the dice outcomes.
The following rules have been implemented: 
- Pig Out: If any of the dice outcomes is a 1, the current player's score for the turn is 1.
- Free Bacon: A player who chooses to roll zero dice scores one more than the largest digit in the opponent's total score.
- Hogtimus Prime: If a player's score for the turn is a prime number, then the turn score is increased to the next larger prime number. 
- Perfect Piggy: If a player's score for the turn is not a 1, but is a perfect square or a perfect cube, the player scores the turn score but swaps the normal six-  sided dice with four-sided dice for all subsequent turns. The next time either player activates Perfect Piggy, the six-sided dice will be swapped back. Subsequent activations of Perfect Piggy will continue swapping the dice.
- Swine Swap: After the turn score is added, if one of the scores is double the other, then the two scores are swapped.

