# WordHunt Solver

A lightweight solver for the popular iMessage game WordHunt.

# What is WordHunt?

WordHunt is a game where players are given a 4x4 board of letters and drag their finger along the board to make as many words as possible in under a minute and 30 seconds. The more words that a player makes, the more points they get, and the longer the words, the higher their score is as well. The player with the highest score at the end of the time limit wins the game.

# How It Works
It implements DFS and a Trie data structure to compute a list of all the optimum and possible valid words (and paths), given a board in the game. Check out the code for more detail!

# How To Use

1. [Download](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) the Github Repository

2. Run "run.exe" through Command Line or simply double clicking.

3. Input in the board from left to right:

i.e. Board:         Input:
*      
*      a b c d        abcdefghijklmnop
*      e f g h
*      i j k l
*      m n o p
*

4. Enter in the solutions to the game and enjoy victory.