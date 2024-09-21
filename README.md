# Flappy-Bird
A game similar to Flappy Bird built in C

How does it work? 
State_alt.c: 
It finds the last platform (the set is sorted)
It finds the current platform, starting from the x position of the ball and tracking onwards.
It finds the next platform, which then becomes the current platform.

State.c does the same as state_alt but it does so using a vector, which is less efficient.

The project requires the VcXsrv tool to run properly, and the raylib library is used for the graphics.

This project was completed for the course Data Structures, by professor Kostas Chatzikokolakis, Department of Informatics and Telecommunications(DIT), University of Athens (UOA). More information can be found here: https://www.di.uoa.gr/en/studies/undergraduate/34
