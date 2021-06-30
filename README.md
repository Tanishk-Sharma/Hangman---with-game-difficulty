# Hangman Game

## How to Play

- Start terminal/command prompt
- Run: ```python hangman_game.py```

- User has to select 1 of 3 difficulty modes:
    1. Easy
    2. Medium
    3. Difficult
    

- These modes help determine below 2 game parameters:
    1. Number of incorrect attempts
    2. Length of chosen word

## Game Difficulty modes:

| Mode      | Number of turns | Minimum length of chosen word |
|-----------|-----------------|-------------------------------|
| EASY      | 12              | 6                             |
| MEDIUM    | 6               | 8                             |
| DIFFICULT | 3               | 10                            |


## Files explained:

1. hangman_game.py: This is the code that runs the entire game.
2. hangman_stages.py: This is simple to store the hangman appearance as the game progress, i.e. as the number of turns remaing decreases.
3. easy.py, medium.py, difficult.py: These files store the list of words according to word length permitted by the game difficulty respectively.


## Sample Screen view:

THE HANGMAN GAME
================

Turns remaining: 1

              +---+
              |   |
              O   |
             /|\  |
             /    |
                  |
            =========
* * * * L * * *
Already Guessed: Q I S W L A
New Guess: s
