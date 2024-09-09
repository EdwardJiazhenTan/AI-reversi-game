# Reversi AI Agent

This project is a Reversi (Othello) AI agent implemented in Java. The AI uses the Mini-Max algorithm with Alpha-Beta pruning to make optimal moves within the game. The entire implementation is less than 1000 lines of code.

## Basic Rules

1. **Initial Setup:** The board starts with four discs in the center: two white and two black. Each player controls one color (black or white).
2. **Turns:** Players take turns placing their discs on the board.
3. **Valid Moves:** A move is valid if it captures at least one of the opponent's discs. Discs are captured by sandwiching them between the newly placed disc and another disc of the player's color in a straight line (horizontal, vertical, or diagonal).
4. **End of the Game:** The game ends when neither player can make a valid move, or the board is full. The player with the most discs of their color at the end of the game wins.

## Features

- **Mini-Max Algorithm:** The AI determines the best possible move by simulating future game states and selecting the optimal path.
- **Alpha-Beta Pruning:** To optimize the Mini-Max search, Alpha-Beta pruning is implemented, reducing the number of nodes that need to be evaluated.
- **Command-Line Interface:** Play the game via the terminal.

## Getting Started

Below is an example of how the game looks during gameplay:

![Reversi AI Example](assets/example.png)

### Prerequisites

- Java Development Kit (JDK) 8 or later.

### Running the Application

1. **Compile the Code:**

   ``` 
   javac Main.java
   java Main
   ```
