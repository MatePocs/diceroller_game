# Dice Roller Game
In this project, I am solving a dice rolling game. The game is set up with n pieces of 6-sided dice, one is rolled, the player can decide if they want to continue rolling. If they stop at any point, the result of the game is the current die value. If they run out of dice (e.i. the nth dice is rolled after n-1 decisions by the player that all asked the game to continue), the result of the game is the current die value, the player has no more decision to make. Goal is to maximise the expected results on the long term. 
I am setting up the strategy to maximise this game. 

See blogpost on Medium for more details:

The project contains three Jupyter Notebooks: 
- diceroller_stats.ipynb: basic calculations
- diceroller_strattesting.ipynb: an environment that tests the results of different strategies
- diceroller_reinflearn.ipynb: in this model, the algorithm uses reinforcement learning to identify the optimal strategy
