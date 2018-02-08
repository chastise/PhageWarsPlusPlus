# PhageWarsPlusPlus
An AI project I created for an intro-to-programming course in the Fall of 2010.

```
  .=================================================================.
  :*-------*       *       *       *-------*       *       *       *:  
  :| C1:+5 |                       | C2:+3 |                        :  
  :| P1:15 |                       | P1:05 |                        :  
  :*-------*       *       *       *-------*       *       *       *:  
  :                                                                 :  
  :                                                                 :  
  :*       *       *       *---------------*       *       *       *:  
  :                        |PhageWars++.scm|                        :  
  :                        |               |                        :  
  :*       *       *       *---------------*       *       *       *:  
  :                                                                 :  
  :                                                                 :  
  :*       *       *       *-------*       *       *       *-------*:  
  :                        | C3:+3 | 10:C3                 | C4:+5 |:  
  :                        |  N:0  |   P2                  | P2:10 |:  
  :*       *       *       *-------*       *       *       *-------*:  
  `=================================================================`
  .=Queue===========================================================.
  :  10:C3 :                                                        :
  :  P2:01 :                                                        :
  `=Enrage: 1.1===========================================Turn: 11=='
```

The files here have been cleaned up to remove class-specific information, such
as TA details, grading information and submission instructions. However, the
majority of the code is as it was during the course in 2010.


## Game Description

[PhageWars](https://armorgames.com/play/2675/phage-wars) is a player-versus-player game about capturing
bases and outsmarting your opponent. This version, designed as an AI project
using the MIT-Scheme programming language, converts PhageWars to a turn-based
game where players are programmed in advance, using basic artificial
intelligence algorithms such as searches and opponent-move-prediction.

Check out the full rules in the [writeup](writeup.txt), but the basic premise of
the game is as follows:

> In this game, there exists a board which contains several numbered cells. Each
  cell has an owner, either Player 1, Player 2, or Neutral (not yet owned).
  The goal of the game is for one player to eliminate all of the cells owned by the other
  player. On each turn, players will be asked to make at most one move for
  each of their cells. Then, the game will process the moves made by each
  player, based on the board layout. Finally, each cell owned by a player is
  given more units based on its cell growth (explained below), and the cycle
  repeats.


## Some Context

Because this project hasn't been touched in years, I don't expect to do any
further development on it. I can't guarantee anything about the functionality of
the code. I've uploaded it here for posterity.
