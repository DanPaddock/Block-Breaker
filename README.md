So just as a little in-sight before I say what scripts to review, I made a basic block-breaker game with a start-screen, 2 different levels and replay functionality.

Scripts to Review
====================

SceneLoader
---------------------
This was used to handle the transition between different scenes in the game, such as Start, Level1, Level2 and GameOver.

ScriptBlock
---------------------
This script handled all interactions with the blocks, such as changing the sprite depending on the damage taken. 

Ball
---------------------
The ball script handled all the logic relating to the ball, such as keeping it on screen and handling collisions.

Paddle
---------------------
The paddle script was used to handle all the logic relating to the paddle, such as keeping it on screen and keeping the ball on the paddle at the start of a level.
