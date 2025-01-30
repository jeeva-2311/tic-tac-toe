# Tic-Tac-Toe Game

Welcome to the **Tic-Tac-Toe** game built with React! This game allows two players to take turns marking the grid with **"X"** and **"O"** symbols. The winner is determined when a player successfully aligns three symbols in a row, column, or diagonal.

---

## Features
- **Two-player gameplay**: Player X and Player O alternate turns to place their symbols on the grid.
- **Dynamic game board**: The board updates as players make their moves.
- **Game result**: The game announces a winner or indicates if it's a draw.
- **Player name editing**: Players can edit their names at any time during the game.
- **Game log**: A log of moves is maintained for players to review.
- **Rematch functionality**: After the game ends, players can restart for a new match.

---

## Project Structure
The project is divided into the following components:

- **`App.js`**: The main component that handles game logic and state management.
- **`Player.js`**: Displays player names and symbols, with the ability to edit player names.
- **`Gameboard.js`**: Displays the game grid and handles player input for selecting squares.
- **`GameOver.js`**: Displays the game result, either the winner or a draw, and allows the option to restart the game.
- **`Log.js`**: Displays a log of players' moves during the game.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jeeva-2311/tic-tac-toe

2. cd tic-tac-toe
3. npm install
4. npm start
5. Open the browser at http://localhost:3000 to play the game.

## Game FLow
- Starting the Game: Once the game begins, players alternate turns. The active player is highlighted.
- Making Moves: Players click on a square to place their symbol. Squares already marked by either player are disabled.
- Game Over: Once a winner is found or all squares are filled, the game ends, and the result is displayed.
- Rematch: After a game is over, players can choose to start a new game by clicking "Rematch."

## Contributing
Feel free to fork this project and submit pull requests. Any suggestions or improvements are welcome!
