# Tic Tac Toe

A Java Swing implementation of the classic two-player Tic Tac Toe game, with score tracking and result dialogs.

## Features

- Two-player turn-based gameplay
- Automatic win detection for rows, columns, and diagonals
- Draw detection when the board is full
- Scoreboard and reset button

## Files

- `App.java` — application entry point and Swing EDT launcher
- `TicTacToeGui.java` — main game UI, button grid, and game logic
- `CommonConstants.java` — shared UI constants and layout values

## Run

```powershell
cd "Tic Tac Toe"
javac -d out src\*.java
java -cp out App
```

This project uses only Java SE and Swing.