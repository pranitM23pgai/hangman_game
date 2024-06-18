

---

# Hangman Game

Welcome to the Hangman Game! This is a simple command-line version of the classic word guessing game. The objective is to guess the hidden word by suggesting letters within a certain number of guesses.

## Table of Contents

- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Setup](#setup)
- [Running the Game](#running-the-game)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Hangman is a word-guessing game. The player tries to guess the hidden word by suggesting letters one at a time. The game ends when the player either guesses the word correctly or runs out of lives.

## How to Play

1. The game will randomly select a word from a predefined list.
2. You have a limited number of lives (6 by default) to guess the word.
3. For each incorrect guess, you lose a life.
4. The game ends when you either guess all the letters correctly or run out of lives.

## Setup

    ```

## Running the Game

1. Run the Python script to start the game:
    ```bash
    python hangman.py
    ```

2. Follow the on-screen prompts to guess letters and play the game.

## Project Structure

- `hangman.py`: The main script that runs the game.
- `hangman_words.py`: Contains the list of words used in the game.
- `hangman_art.py`: Contains the ASCII art for the hangman stages and the game logo.

### Sample Project Structure

```
hangman-game/
│
├── hangman.py
├── hangman_words.py
├── hangman_art.py

```

### `hangman_words.py`

This file contains a list of words that the game randomly chooses from.

```python
# Sample content of hangman_words.py
word_list = ["python", "java", "kotlin", "javascript"]
```

### `hangman_art.py`

This file contains ASCII art for the hangman stages and the game logo.

```python
# Sample content of hangman_art.py
logo = """
 _                                             
| |                                            
| |__   __ _ _ __   __ _ _ __ ___   __ _ _ __  
| '_ \ / _` | '_ \ / _` | '_ ` _ \ / _` | '_ \ 
| | | | (_| | | | | (_| | | | | | | (_| | | | |
|_| |_|\__,_|_| |_|\__, |_| |_| |_|\__,_|_| |_|
                    __/ |                      
                   |___/                       
"""

stages = ['''
  +---+
  |   |
  O   |
 /|\  |
 / \  |
      |
=========
''', ''' (remaining stages...) '']
```

## Dependencies

- Python 3.x
- No external libraries are required for this project.



---

