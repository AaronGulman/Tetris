# Tetris Game

## Overview

This project is a C# implementation of the classic Tetris game using WPF (Windows Presentation Foundation). The game includes various Tetromino shapes, a game grid for placing the blocks, and a graphical interface for playing the game.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Classes Description](#classes-description)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Features

- **Classic Tetris Gameplay**: Rotate, move, and place Tetrominoes on the game grid.
- **Score Tracking**: Keep track of the player's score.
- **Game Over Screen**: Display the final score and option to play again.
- **Next Block Preview**: Shows the next Tetromino to appear.
- **Hold Functionality**: Hold a Tetromino for later use.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Tetris.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Tetris
   ```
3. **Open the solution in Visual Studio**:
   ```bash
   Tetris.sln
   ```
4. **Restore NuGet packages**: Visual Studio should automatically restore any required NuGet packages when you open the solution.
5. **Build the project**: Press `Ctrl+Shift+B` to build the solution.

## Usage

1. **Run the project**: Press `F5` or click the Start button in Visual Studio to run the application.
2. **Controls**:
   - **Arrow keys** to move the Tetromino left, right, and down.
   - **Up arrow** to rotate the Tetromino clockwise.
   - **Space bar** to drop the Tetromino instantly.
   - **Shift** to hold the current Tetromino.

## Project Structure

```plaintext
Tetris/
├── Assets/                 # Contains game assets like images and icons
│   ├── Background.png
│   └── Icon.ico
├── App.xaml                # Application definition and resources
├── App.xaml.cs             # Application startup logic
├── AssemblyInfo.cs         # Assembly metadata
├── Block.cs                # Base class for all Tetrominoes
├── BlockQueue.cs           # Manages the sequence of upcoming Tetrominoes
├── GameGrid.cs             # Handles the game grid logic
├── GameState.cs            # Manages the overall game state and logic
├── IBlock.cs               # Interface for Tetrominoes
├── JBlock.cs               # J-shaped Tetromino
├── LBlock.cs               # L-shaped Tetromino
├── MainWindow.xaml         # XAML layout for the main game window
├── MainWindow.xaml.cs      # Logic for the main game window
├── OBlock.cs               # O-shaped Tetromino
├── Position.cs             # Represents a position on the grid
├── SBlock.cs               # S-shaped Tetromino
├── TBlock.cs               # T-shaped Tetromino
├── Tetris.csproj           # C# project file
├── Tetris.sln              # Visual Studio solution file
└── ZBlock.cs               # Z-shaped Tetromino
```

## Acknowledgements

This project is inspired by the classic Tetris game. The implementation is a basic version and can be further extended with features like different levels, high scores, and more advanced graphics.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
