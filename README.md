
# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with HTML, CSS, and JavaScript. Play against a friend in this interactive two-player game.

## Features

- **Two-Player Gameplay**: Players alternate between X and O
- **Win Detection**: Automatically detects winning patterns
- **Draw Detection**: Identifies when the game ends in a draw
- **Game Reset**: Easy reset functionality to start a new game
- **Responsive Design**: Adjustable grid layout for different screen sizes

## How to Play

1. Open `index.html` in your web browser
2. Players take turns clicking on empty boxes to place their mark (O or X)
3. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
4. If all 9 boxes are filled with no winner, the game is a draw
5. Click **Reset Game** to start a new game

## Game Files

- **index.html** - Main HTML structure with the game board and buttons
- **index.css** - Styling for the game interface
- **index.js** - Game logic including:
  - Turn management (O and X)
  - Win pattern checking
  - Draw detection
  - Game reset functionality

## Win Patterns

The game checks for wins on these 8 possible combinations:
- Rows: [0,1,2], [3,4,5], [6,7,8]
- Columns: [0,3,6], [1,4,7], [2,5,8]
- Diagonals: [0,4,8], [2,4,6]

## Game Controls

- **Reset Game**: Clear the board and start a new game
- **New Game** (shown after a win/draw): Start a fresh game

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript

---

Enjoy the game! 🎮
