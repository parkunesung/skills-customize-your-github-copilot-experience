# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a command-line Hangman game to practice Python strings, loops, conditionals, random selection, and user input. Players will guess a hidden word one letter at a time before they run out of attempts.

## 📝 Tasks

### 🛠️ Create the Hidden Word and Game State

#### Description
Set up the game by choosing a word at random from a predefined word list and preparing the state needed to track the player's progress.

#### Requirements
Completed program should:

- Select one word at random from a list containing at least five words.
- Display each letter in the word as an underscore at the start of the game.
- Set and track a limit for incorrect guesses.


### 🛠️ Implement the Guessing Loop

#### Description
Let the player enter letter guesses until they reveal the word or use all their incorrect guesses.

#### Requirements
Completed program should:

- Accept a letter guess from the player on each turn.
- Reveal correctly guessed letters in their matching positions and keep unguessed letters hidden.
- Reduce the remaining attempts when the player guesses a letter that is not in the word.
- End when the word is revealed or no attempts remain, and display a clear win or lose message.
