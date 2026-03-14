
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a text-based Hangman game in Python to practice strings, loops, conditionals, and user input handling.

## 📝 Tasks

### 🛠️ Game Setup

#### Description
Prepare the game by defining a list of words, selecting a secret word at random, and initializing game state variables.

#### Requirements
Completed program should:

- Use `random.choice()` to select a word from a predefined list of at least 10 words
- Initialize a hidden display for the word using underscores for unknown letters
- Track guessed letters, remaining attempts, and player progress

### 🛠️ Guess Handling and State Update

#### Description
Process player guesses, update the displayed word, and reject invalid or repeated entries.

#### Requirements
Completed program should:

- Prompt the user for one letter per guess
- Validate input (single alphabetic character, not guessed before)
- Reveal guessed letters in the display string for correct guesses
- Decrement remaining attempts for incorrect guesses

### 🛠️ Win/Lose Logic and Endgame

#### Description
Determine game outcome, show feedback, and allow players to play again.

#### Requirements
Completed program should:

- Declare a win when all letters are guessed
- Declare a lose when attempts reach zero and reveal the secret word
- Display current progress (`_ a _ g _ a _`) and remaining attempts after each guess
- Optionally ask the player if they want to play another round

