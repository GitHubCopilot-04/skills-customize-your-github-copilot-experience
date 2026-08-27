# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a classic Hangman game in Python to practice loops, conditionals, string handling, and user input. By completing this assignment, you will create a playable terminal game with clear game rules and win/lose outcomes.

## 📝 Tasks

### 🛠️	Build the Core Game Loop

#### Description
Create the main Hangman gameplay loop where the player repeatedly guesses letters until they either guess the full word or run out of attempts.

#### Requirements
Completed program should:

- Randomly select one word from a predefined list of words.
- Accept one letter guess from the user each turn.
- Reveal correct letters in their proper positions using a progress display like `_ _ _ _`.


### 🛠️	Track Attempts and End Conditions

#### Description
Add game state tracking for incorrect guesses and complete the game with clear final outcomes.

#### Requirements
Completed program should:

- Reduce remaining attempts only for incorrect guesses.
- End the game when the player guesses all letters in the word.
- End the game when attempts reach zero and display an appropriate win or lose message.
