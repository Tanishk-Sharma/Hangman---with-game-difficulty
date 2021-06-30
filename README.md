# Hangman Game

## How to Play

- Start terminal/command prompt
- Run: ```python hangman_game.py```

- Player has to select 1 of 3 difficulty modes:
    1. Easy
    2. Medium
    3. Difficult
    

- These modes help determine below 2 game parameters:
    1. Number of incorrect attempts
    2. Length of chosen word

## Game Difficulty modes:

| Modes     | Number of turns                                      | Length of chosen word |
|-----------|------------------------------------------------------|-----------------------|
| EASY      | 3 times the number of unique letters in chosen word  | 6                     |
| MEDIUM    | 2 times the number of unique letters in chosen word  | 8                     |
| DIFFICULT | Equal to the number of unique letters in chosen word | 10                    |

## Files explained:

1. hangman_game.py: This is the code that runs the entire game.
2. hangman_stages.py: This is simple to store the hangman appearance as the game progress, i.e. as the number of turns remaing decreases.
3. easy.py, medium.py, difficult.py: These files store the list of words according to word length permitted by the game difficulty respectively.


## Sample Screen view:

![image](https://user-images.githubusercontent.com/32167236/124026681-9db23a80-da0f-11eb-89c5-d06c73bd134a.png)


