# Tic-Tac-Toe Game with Scoreboard

This project implements a **Tic-Tac-Toe** game using **HTML**, **CSS**, and **JavaScript**, where players can track their scores (Wins for X and O). The game includes functionalities for starting a new game, resetting scores, and detecting win/loss or draw scenarios.

---

## Features

- **Interactive Gameplay**:
  - Click buttons to make a move as Player X or Player O.
  - Alternating turns between X and O players.

- **Win Detection**:
  - Automatically checks for winning conditions after each move.
  - Alerts the winner and updates the scoreboard.

- **Draw Detection**:
  - Identifies when all cells are filled without a winner.
  - Declares the game as a "Draw" and resets the board.

- **New Game Functionality**:
  - Resets the game board while maintaining the score.

- **Scoreboard Management**:
  - Displays scores for both X and O players.
  - Includes functionality to reset the scoreboard.

---

## File Structure

- `index.html`: Contains the HTML structure of the game.
- `style.css`: External CSS file to style the game board (optional for enhancement).
- Embedded JavaScript: Implements the game logic.

---

## Usage

1. Open `index.html` in your web browser.
2. Play the game by clicking the buttons to mark cells as X or O.
3. Check the scoreboard for win/loss counts.
4. Click **New Game** to reset the board or **Clear Scores** (via the script) to reset the scoreboard.

---

## Game Rules

1. The game starts with Player X's turn.
2. Players take turns clicking an empty cell on the grid:
   - Player X marks **X**.
   - Player O marks **O**.
3. The game automatically checks after each move for:
   - **Winning Conditions** (three consecutive marks horizontally, vertically, or diagonally).
   - **Draw** (all cells filled with no winner).
4. Alerts will display the winner or draw result.
5. A **New Game** can be initiated to restart the board.

---

## Technical Details

### JavaScript Functions

- `play()`:
  Handles player moves and updates the board.
  
- `NewGame()`:
  Resets the game board to the initial state.

- `ClearScores()`:
  Resets the scoreboard.

- `CheckWin()`:
  Checks for winning conditions after each move.

- `Drew()`:
  Detects a draw and resets the board if no moves are left.

- `updateScore(winner)`:
  Updates and displays the scores for the winning player (X or O).

---

## Enhancements

You can further improve the game by:
- Adding a **CSS grid** for better layout and styling.
- Highlighting the winning combination when a player wins.
- Adding AI for single-player gameplay.

---

## Installation

1. Download or clone the repository.
2. Place all files in the same directory.
3. Open `index.html` in your browser.

---
