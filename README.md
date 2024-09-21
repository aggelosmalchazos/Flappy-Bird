# Flappy-Bird
A game similar to Flappy Bird built in C

How does it work? 
State_alt.c: 
It finds the last platform (the set is sorted)
It finds the current platform, starting from the x position of the ball and tracking onwards.
It finds the next platform, which then becomes the current platform.

State.c does the same as state_alt but it does so using a vector, which is less efficient.

The project requires the VcXsrv tool to run properly, and the raylib library is used for the graphics.
