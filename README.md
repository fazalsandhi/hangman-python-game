
# Hangman Python Game

Welcome to **Hangman Python Game**! This is a terminal-based implementation of the classic word-guessing game, Hangman. The game is built in Python and includes a list of tricky words to guess and some fun ASCII art.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

Hangman is a simple word-guessing game where the player has to guess the word one letter at a time. Every incorrect guess costs the player a "life." If you run out of lives, you lose the game. But if you guess all the letters correctly, you win!

This Python version includes:
- A list of challenging words
- Fun ASCII art to visually represent your progress
- Randomized word selection for a new challenge every time you play

## Features

- Random word selection from a list of over 200 words.
- ASCII art to represent the hanging stages.
- User input for letter guesses.
- Track incorrect guesses and remaining lives.
- Win or lose based on the number of correct guesses.

## How to Play

1. You will be shown an empty word represented by underscores (`_`).
2. Guess one letter at a time by typing and hitting Enter.
3. If you guess a correct letter, it will be revealed in the word.
4. If you guess wrong, you'll lose a life, and part of the hangman will be drawn.
5. You have 6 lives to guess the word before the hangman is fully drawn, and you lose the game.
6. Win the game by guessing all the correct letters in the word.

## Installation

To play the game locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/fazalsandhi/hangman-python-game.git
```

2. Navigate to the project directory:

```bash
cd hangman-python-game
```

3. Ensure you have Python installed on your system. You can download it from [here](https://www.python.org/downloads/).

4. Run the game:

```bash
python main.py
```

## Usage

When you run the script, you will be prompted to guess a letter. After each guess, the game will show the updated word and remaining lives.

**Example:**
```
Word to guess: _ _ _ _ _ _
Guess a letter: e
Word to guess: _ _ e _ _ _
```

The game ends when either:
- You correctly guess all the letters (You win!)
- You run out of lives (You lose, and the word is revealed).
