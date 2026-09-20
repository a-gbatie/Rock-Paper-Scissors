# Rock-Paper-Scissors

Rock-Paper-Scissors is a command-line game built with Node.js. Players compete against the computer by choosing Rock, Paper, or Scissors and receive immediate feedback on each round.

This project demonstrates foundational Command-Line Interface (CLI) concepts, JavaScript game logic, project structure, and interactive terminal menus.

## Features

- Play Rock-Paper-Scissors against the computer
- Choose Rock, Paper, or Scissors using an interactive command-line menu
- Computer selections are randomly generated
- Receive immediate feedback after each round
- Track wins, losses, and ties
- View game statistics
- Reset game statistics
- Return to the main menu or quit the game

## Installation

Clone the repository and install the dependencies:

```bash
npm install
```

## Running the Game

Run the game with:

```bash
node bin/index.js
```

## How to Play

1. Select **Play Game** from the main menu.
2. Choose Rock, Paper, or Scissors.
3. The computer randomly selects its choice.
4. The game determines the winner.
5. Your win, loss, or tie statistics are updated.
6. Continue playing, view your statistics, reset your statistics, or quit the game.

## Game Rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- Matching choices result in a tie

## Technologies Used

- JavaScript
- Node.js
- Inquirer
- Chalk
- Commander

## JavaScript Concepts

This project demonstrates:

- Functions
- Objects
- Conditional logic
- `switch` statements
- Random number generation with `Math.random()`
- `async` / `await`
- ES modules with `import` and `export`
- Shared application state
- Command-line user interaction

## Project Structure

```text
rock-paper-scissors-cli
├── bin
│   └── index.js
├── package.json
└── src
    └── lib
        ├── gameLogic.js
        └── state.js
```

## Author

Created by a-gbatie
