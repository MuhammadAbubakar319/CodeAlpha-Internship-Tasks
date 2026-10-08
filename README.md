[README_Chatbot.md](https://github.com/user-attachments/files/33197107/README_Chatbot.md)
# Basic Rule-Based Chatbot

A simple console-based rule-based chatbot built with Python. The chatbot accepts user messages and responds using predefined rules and responses.

## Project Overview

This project demonstrates how basic Python programming concepts can be used to create a simple interactive chatbot without external APIs, artificial intelligence services, or third-party libraries.

The chatbot recognizes common messages such as greetings, questions about how it is doing, and goodbye messages. It continues the conversation until the user chooses to exit.

## Features

- Interactive command-line conversation.
- Recognizes common user messages.
- Provides predefined responses.
- Uses a continuous conversation loop.
- Supports messages such as:
  - `hello`
  - `how are you`
  - `bye`
- Provides a clear goodbye response when the user exits.
- Uses simple rule-based decision making.
- Requires no internet connection or external API.

## Concepts Used

This project demonstrates the following Python concepts:

- Functions
- `if / elif / else` statements
- `while` loops
- Strings
- User input and console output
- Basic rule-based logic

## How the Chatbot Works

1. The program starts the chatbot.
2. The user enters a message in the console.
3. The chatbot checks the message against predefined rules.
4. A suitable response is selected based on the user's input.
5. The conversation continues inside a loop.
6. When the user enters `bye`, the chatbot responds with a goodbye message and exits.

## Supported Inputs

| User Input | Chatbot Response |
|---|---|
| `hello` | `Hi!` |
| `how are you` | `I'm fine, thanks!` |
| `bye` | `Goodbye!` |

Other inputs can be handled by adding additional rules and responses to the program.

## How to Run

Make sure Python 3 is installed on your computer.

Run the program from the terminal:

```bash
python chatbot.py
```

## Example

```text
Basic Chatbot
Type 'bye' to exit.

You: hello
Bot: Hi!

You: how are you
Bot: I'm fine, thanks!

You: bye
Bot: Goodbye!
```

## Project Structure

```text
chatbot-project/
│
├── chatbot.py
└── README.md
```

## Requirements

- Python 3.x
- No external Python packages are required.
- No API key or internet connection is required.

## Learning Objectives

By completing this project, you can practice:

- Creating and using Python functions.
- Working with strings.
- Using conditional statements.
- Creating loops for repeated interaction.
- Handling user input and displaying output.
- Designing simple rule-based program logic.

## Future Improvements

The chatbot can be extended with features such as:

- Adding more questions and responses.
- Supporting different variations of the same message.
- Making input handling fully case-insensitive.
- Adding more conversation topics.
- Adding a help command.
- Storing conversation history.
- Connecting the chatbot to an external AI API in a future version.
- Developing a graphical user interface.

## Limitations

This is a basic rule-based chatbot, so it does not understand natural language like an AI assistant. It responds only to messages that match the predefined rules in the program.

## Author

**Basic Rule-Based Chatbot**

Developed as a Python learning project to practice functions, loops, conditional statements, strings, and input/output.

## License

This project is intended for educational and learning purposes.
