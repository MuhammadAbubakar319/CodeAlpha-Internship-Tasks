(https://github.com/user-attachments/files/33197075/README_Hangman.md)# Hangman Game

A simple text-based Hangman game built with Python. The player attempts to guess a randomly selected word one letter at a time.

## Project Overview

This project is designed to demonstrate fundamental Python programming concepts through a small interactive console game.

The game selects one word from a predefined list of five words. The player guesses letters until the complete word is revealed or the maximum number of incorrect guesses is reached.

## Features

- Uses a predefined list of 5 words.
- Selects a word randomly for each game.
- Allows the player to guess one letter at a time.
- Displays the current progress of the hidden word.
- Tracks incorrect guesses.
- Allows a maximum of **6 incorrect guesses**.
- Displays a win or loss message.
- Runs directly in the Python console.
- Requires no external files, APIs, graphics, or audio.

## Concepts Used

This project demonstrates the following Python concepts:

- `random` module
- Lists
- Strings
- `while` loops
- `if / elif / else` statements
- User input and console output
- Basic game logic

## How the Game Works

1. The program contains a list of five predefined words.
2. A word is randomly selected using Python's `random` module.
3. The selected word is hidden from the player.
4. The player enters one letter at a time.
5. If the letter exists in the word, its position is revealed.
6. If the letter is incorrect, the number of remaining attempts decreases.
7. The player wins when all letters are correctly guessed.
8. The player loses after 6 incorrect guesses.

## How to Run

Make sure Python 3 is installed on your computer.

Run the program from the terminal:

```bash
python hangman.py
```

## Example

```text
Welcome to Hangman!

Word: _ _ _ _ _

Incorrect guesses remaining: 6

Enter a letter: a
Good guess!

Word: _ a _ _ _

Enter a letter: z
Incorrect guess!

Incorrect guesses remaining: 5
```

## Project Structure

```text
hangman-project/
│
├── hangman.py
└── README.md
```

## Requirements

- Python 3.x
- No external packages are required.

## Learning Objectives

By completing this project, you can practice:

- Working with Python lists and strings.
- Using random selection.
- Creating and controlling `while` loops.
- Writing conditional statements.
- Handling user input.
- Building basic interactive program logic.

## Future Improvements

The project can be extended with additional features such as:

- Adding more words.
- Adding different difficulty levels.
- Preventing repeated guesses.
- Adding a scoring system.
- Displaying a visual Hangman figure.
- Loading words from an external file.
- Adding replay functionality.

## Author

**Python Hangman Game**

Developed as a beginner Python project for practicing core programming concepts.

## License

This project is intended for educational and learning purposes.
