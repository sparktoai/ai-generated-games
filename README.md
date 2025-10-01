# Schulte Table Training Game & 2048 Game & Sudoku Game

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Web-green.svg)
![Language](https://img.shields.io/badge/language-JavaScript-yellow.svg)

## Project Overview

The Schulte Table Training Game is a web-based attention training tool designed to help users improve focus, visual search ability, and cognitive processing speed. It uses the classic Schulte grid training method to exercise the brain by sequentially finding and clicking randomly arranged numbers.

We've also added the classic 2048 puzzle game, a number merging game that challenges players to slide numbered tiles on a grid to combine them and create a tile with the number 2048.

Additionally, we've included the classic Sudoku puzzle game, a number logic puzzle that challenges players to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 sub-grids contains all digits from 1 to 9.

## Features

### Schulte Table Training Game
- 🎮 **Multiple Difficulty Levels**: Supports 3×3, 5×5, 7×7, and 8×8 grids
- 🌍 **Multi-language Support**: Available in both English and Chinese versions
- ⏱️ **Real-time Timer**: Accurately records completion time
- 📊 **Performance Evaluation**: Provides intelligent assessment based on completion time and difficulty
- 📈 **History Tracking**: Automatically saves the last 10 training records
- 🎨 **Responsive Design**: Adapts to various device screens
- 💾 **Local Storage**: Uses browser localStorage to save data
- ✅ **Instant Feedback**: Visual feedback for correct and incorrect actions

### 2048 Game
- 🎮 **Classic 4x4 Grid**: Traditional 2048 gameplay experience
- 🌍 **Multi-language Support**: Available in both English and Chinese versions
- 📊 **Score Tracking**: Real-time score calculation and best score storage
- 🎨 **Responsive Design**: Works on desktop, tablet, and mobile devices
- ⌨️ **Keyboard Controls**: Support for arrow keys navigation
- 👆 **Touch Support**: Swipe gestures for mobile play
- 💾 **Local Storage**: Best score saved in browser localStorage
- ✨ **Smooth Animations**: Tile movement and merge animations

### Sudoku Game
- 🎮 **9×9 Standard Grid**: Classic Sudoku puzzle experience
- 🌍 **Multi-language Support**: Available in both English and Chinese versions
- 🎲 **Multiple Difficulty Levels**: Easy, Medium, and Hard difficulty options
- 📄 **Visual Feedback**: Selected cell highlighting, same number highlighting, and error marking
- 💡 **Hint System**: Smart hint feature to help solve puzzles
- ✅ **Solution Checking**: Real-time error detection and solution validation
- ⏱️ **Timer**: Built-in timer to track solving time
- 🎨 **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- ⌨️ **Keyboard Support**: Number input and arrow key navigation
- 👆 **Touch Support**: Touch-friendly interface for mobile devices

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- localStorage API

## Demo

### Schulte Table Training Game
- [English Version](https://sparktoai.com/ai-generated-games/schulte-table-game.html)
- [Chinese Version](https://sparktoai.com/zh/ai-generated-games/schulte-table-game.html)

### 2048 Game
- [English Version](https://sparktoai.com/ai-generated-games/2048-game.html)
- [Chinese Version](https://sparktoai.com/zh/ai-generated-games/2048-game.html)

### Sudoku Game
- [English Version](https://sparktoai.com/ai-generated-games/sudoku-game.html)
- [Chinese Version](https://sparktoai.com/zh/ai-generated-games/sudoku-game.html)

## Development Process

### Schulte Table Training Game
- [English Version](https://sparktoai.com/articles/schulte-table-game.html)
- [Chinese Version](https://sparktoai.com/zh/articles/schulte-table-game.html)

### 2048 Game
- [English Version](https://sparktoai.com/articles/2048-game.html)
- [Chinese Version](https://sparktoai.com/zh/articles/2048-game.html)

### Sudoku Game
- [English Version](https://sparktoai.com/articles/sudoku-game.html)
- [Chinese Version](https://sparktoai.com/zh/articles/sudoku-game.html)

## Quick Start

### Online Experience

Open one of the following files directly in your browser:

#### Schulte Table Training Game
- English version: `schulte-table-game.html`
- Chinese version: `zh/schulte-table-game.html`

#### 2048 Game
- English version: `2048-game.html`
- Chinese version: `zh/2048-game.html`

#### Sudoku Game
- English version: `sudoku-game.html`
- Chinese version: `zh/sudoku-game.html`

### Local Setup

1. Clone or download this repository
2. Open any of the HTML files in your browser:
   - `schulte-table-game.html` or `zh/schulte-table-game.html`
   - `2048-game.html` or `zh/2048-game.html`
   - `sudoku-game.html` or `zh/sudoku-game.html`

### How to Play

#### Schulte Table Training Game
1. Select an appropriate difficulty level
2. Click any number to start the game
3. Click the numbers in sequential order (from 1 to the maximum number)
4. View your completion time and system evaluation
5. Continue training to improve your performance

#### 2048 Game
1. Use arrow keys or swipe gestures to move the tiles
2. Tiles with the same number merge into one when they touch
3. After each move, a new tile (2 or 4) randomly appears
4. Reach the 2048 tile to win
5. The game ends when the board is full and no merges are possible

#### Sudoku Game
1. Select a difficulty level (Easy, Medium, or Hard)
2. Click on an empty cell to select it
3. Enter numbers 1-9 using the number pad or keyboard
4. Use the "Hint" button for help when stuck
5. Use the "Check" button to validate your current progress
6. Complete the puzzle by filling all cells correctly

## Training Principle (Schulte Table)

The Schulte grid is a commonly used method in psychology to study and develop attention. During training, neurons must quickly scan and identify target numbers while suppressing interference from other numbers. Long-term consistent training can:

- Improve visual attention
- Enhance concentration
- Accelerate information processing speed
- Improve visual search ability

## File Structure

```
.
├── zh/
│   ├── schulte-table-game.html  # Chinese version of Schulte Table
│   ├── 2048-game.html           # Chinese version of 2048 Game
│   └── sudoku-game.html         # Chinese version of Sudoku Game
├── README.md                  # Project documentation (English)
├── README_zh.md               # 项目说明文档 (中文)
├── schulte-table-game.html    # English version of Schulte Table
├── 2048-game.html             # English version of 2048 Game
└── sudoku-game.html           # English version of Sudoku Game
```

## Multi-language Documentation

This project provides documentation in both English and Chinese:

- English documentation: `README.md`
- Chinese documentation: `README_zh.md`

## Browser Compatibility

- Chrome 50+
- Firefox 45+
- Safari 10+
- Edge 15+

## Development Notes

This project is built entirely with native web technologies without additional dependencies. The code structure is clear and easy to maintain and extend.

### Code Features

- Object-oriented design (SchulteGridGame class, Game2048 class, SudokuGame class)
- Semantic HTML structure
- Responsive CSS design
- Modular JavaScript implementation

## Contributing

Issues and Pull Requests are welcome to improve this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Thanks to all developers and users who have contributed to this project.