# Trainbot backend

## Theory of operation
A simple programming language that allows you to play with stuff on the screen.

## Top Level Requirements
1. Interpreted language.
1. The updated state should be used by the client to update the screen.
1. Client should only work on the data provided by the backend.
1. Stepping through the program is controlled by the client which will send the program line by line.
1. Collisions of objects on screen may or may not be allowed depending on parameters set in the object's data block.
1. program should be savable and loadable
1. There maybe initial configuration which needs to be saved along with the program
1. Initial configuration consists of Items already on the screen at the time of program start. It sets the boundaries of the game play.
1. The programming language should allow control structures like FOR loop, WHILE loop, IF statements, FUNCTIONS 
1. The language should be extendable
  - you should be allowed to add keywords and statements dynamically
  - type checking and syntax errors should be returned
1. Reset should bring the environment back to initial state
1. User login with password
1. Share projects with url
