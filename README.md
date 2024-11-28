# Snake King Game (Console-based)

This is a simple console-based Snake game implemented in C++. It features a snake that moves around the screen to collect fruits, grows longer as it eats, and the game ends if the snake collides with itself. The game wraps around the edges of the screen, allowing the snake to appear on the opposite side.

## Features
- **Snake Movement**: Use `W`, `A`, `S`, and `D` to control the snake's movement.
- **Fruit Eating**: The snake eats the fruit, which randomly appears on the screen. Each fruit adds 10 points to the score and increases the snake's length.
- **Game Over**: The game ends if the snake collides with itself.
- **Wrap Around**: The snake can move beyond the boundaries of the screen and reappear on the opposite side.

## Installation

To run this project, follow these steps:

### Requirements
- A C++ compiler (e.g., g++, Visual Studio, Code::Blocks, etc.)
- Windows operating system (due to usage of `Windows.h` for `Sleep()`)

### Steps
1. Clone this repository or download the files to your local machine.
2. Open the project in your preferred C++ IDE or compiler.
3. Compile and run the `SnakeKing.cpp` file.

## How to Play

1. When you run the game, you will be prompted to press `'s'` to start.
2. The snake starts in the middle of the screen and you control its movement using the following keys:
   - `W` to move up
   - `A` to move left
   - `S` to move down
   - `D` to move right
3. The objective is to eat as many fruits (`*`) as possible to increase your score. Each time you eat a fruit, your score increases by 10, and your snake grows longer.
4. Avoid colliding with the snake's own body. If the snake bites itself, the game ends.

## Controls
- **W**: Move up
- **A**: Move left
- **S**: Move down
- **D**: Move right

## Code Overview

### Key Functions
- **setup()**: Initializes the game state, including setting the snake's initial position, fruit position, and score.
- **draw()**: Draws the game area, snake, fruit, and score on the console screen.
- **input()**: Captures user input to control the snake's movement.
- **logic()**: Handles the snake's movement, collision detection, fruit consumption, and wrapping around the screen.

### Key Variables
- **headX, headY**: The position of the snake's head.
- **fruitX, fruitY**: The position of the fruit.
- **score**: The player's score.
- **tailx[], taily[]**: Arrays to store the positions of the snake's tail.
- **tail_len**: The length of the snake's tail.
- **gameOver**: A flag to indicate if the game has ended.



https://github.com/user-attachments/assets/ce7d0a53-b126-4eff-8f98-a7d0933dcf85

