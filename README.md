# Dice Roller Game
In this project, I am solving a dice rolling game. The game is set up with n pieces of 6-sided dice, one is rolled, the player can decide if they want to continue rolling. If they stop at any point, the result of the game is the current die value. If they run out of dice (e.i. the nth dice is rolled after (n-1)th 'continue' decisions by the player), the result of the game is the current die value, and the player has no more decision to make. 

Goal is to maximise the expected results on the long term. 

See blogpost my blogpost for more details:

The project contains three Jupyter Notebooks: 
- __diceroller_stats.ipynb__: basic calculations
- __diceroller_strattesting.ipynb__: an environment that tests the results of different strategies
- __diceroller_reinflearn.ipynb__: in this model, the algorithm uses reinforcement learning to identify the optimal strategy
