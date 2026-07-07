# Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with vanilla HTML, CSS, and JavaScript. This project is designed to enhance logic-building skills through interactive gameplay.

## Features

- 🎮 **Interactive Gameplay**: Play against another player with a clean, user-friendly interface
- ✨ **Win Detection**: Automatic detection of winning patterns and draw conditions
- 🔄 **Reset & New Game**: Options to reset the current game or start a new game
- 📱 **Responsive Design**: Works on different screen sizes
- ⚡ **Vanilla JavaScript**: No external dependencies, pure JavaScript implementation

## Game Rules

1. Two players take turns marking spaces on a 3×3 grid
2. The first player uses "O" and the second player uses "X"
3. A player wins by placing three of their marks in a horizontal, vertical, or diagonal row
4. If all 9 spaces are filled without a winner, the game is a draw

## Winning Patterns

The game checks for wins using the following patterns:
- Rows: [0,1,2], [3,4,5], [6,7,8]
- Columns: [0,3,6], [1,4,7], [2,5,8]
- Diagonals: [0,4,8], [2,4,6]

## File Structure

```
Tic-Tac-Toe-Game/
├── index.html      # HTML structure and game layout
├── style.css       # Styling and layout
├── app.js          # Game logic and interactivity
└── README.md       # This file
```

## How to Play

1. Open `index.html` in your web browser
2. Player O makes the first move by clicking on any empty box
3. Player X takes the second turn
4. Players alternate turns until:
   - One player gets three marks in a row (wins)
   - All boxes are filled without a winner (draw)
5. Click **Reset Game** to clear the board and restart
6. Click **New Game** after a game ends to play again

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and layout
- **JavaScript (ES6)**: Game logic and interactivity

## Key JavaScript Functions

- `resetGame()`: Clears the board and resets game state
- `checkWinner()`: Checks all winning patterns after each move
- `showWinner()`: Displays the winner message
- `showDraw()`: Displays a draw message
- `enableBoxes()`: Re-enables all game boxes
- `disableBoxes()`: Disables all game boxes after game ends

## Future Enhancements

- Add score tracking across multiple games
- Implement AI opponent for single-player mode
- Add difficulty levels for AI
- Add sound effects and animations
- Implement game history/undo functionality
- Add themes and customization options

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your favorite web browser
3. Start playing!

## License

This project is open source and available under the MIT License.

## Author

Created by [tiwari-nikhil](https://github.com/tiwari-nikhil)

---

**Enjoy playing Tic-Tac-Toe!** 🎯
