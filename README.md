# SudokuASM - x86 Assembly Sudoku Game

A fully-featured Sudoku game implementation written in pure x86 Assembly language, featuring dynamic puzzle generation, input validation, and advanced gameplay mechanics.

## 🎯 Features

- **Dynamic Board Generation**: Randomly generates valid Sudoku puzzles with multiple solution paths
- **Smart Input Validation**: Comprehensive checking ensures only valid moves are accepted
- **Multiple Solutions Support**: Generated puzzles allow for various valid solving approaches (not hardcoded single-solution boards)
- **Undo Functionality**: Stack-based move tracking allows players to undo their moves
- **Interactive Gameplay**: Full keyboard-driven interface for seamless user experience
- **Pure Assembly**: Written entirely in x86 Assembly for maximum performance and educational value

## 🛠️ Technical Specifications

- **Language**: x86 Assembly
- **Architecture**: 32-bit x86
- **Platform**: Compatible with DOS/Windows environments
- **Assembler**: MASM/NASM compatible
- **Memory Management**: Efficient stack-based operations for move tracking

## 📋 Prerequisites

- x86 Assembly environment (MASM, NASM, or compatible assembler)
- DOS emulator or Windows environment for execution
- Basic understanding of Assembly language (for code modification)

## ⚙️ Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/SudokuASM.git
   cd SudokuASM
   ```

2. **Assemble the code**:
   ```bash
   # For MASM
   masm sudoku.asm
   link sudoku.obj
   
   # For NASM
   nasm -f obj sudoku.asm
   link sudoku.obj
   ```

3. **Run the game**:
   ```bash
   sudoku.exe
   ```

## 🎮 How to Play

### Game Controls
- **Arrow Keys**: Navigate the Sudoku grid
- **Number Keys (1-9)**: Enter numbers into cells
- **Backspace/Delete**: Clear a cell
- **U Key**: Undo last move
- **ESC**: Exit game
- **Enter**: Confirm selection/move

### Game Rules
- Fill the 9×9 grid with digits 1-9
- Each row must contain all digits 1-9 without repetition
- Each column must contain all digits 1-9 without repetition
- Each 3×3 sub-grid must contain all digits 1-9 without repetition

### Features in Action
- **Random Generation**: Each new game presents a unique puzzle
- **Input Validation**: Invalid moves are automatically rejected with feedback
- **Undo System**: Mistakes can be easily corrected using the stack-based undo feature
- **Multiple Solutions**: Puzzles are designed to have various valid solution paths

## 🏗️ Code Architecture

### Core Components

- **Board Generation Engine**: Algorithmic creation of valid Sudoku puzzles
- **Validation System**: Real-time checking of player inputs against Sudoku rules
- **Stack Management**: Efficient move tracking for undo functionality
- **Display Interface**: Console-based rendering of the game board
- **Input Handler**: Keyboard event processing and command interpretation

### Key Algorithms

- **Puzzle Generation**: Backtracking algorithm with randomization
- **Constraint Checking**: Row, column, and box validation routines
- **Move Stack**: LIFO structure for storing and retrieving player moves

## 🧠 Technical Highlights

- **Memory Efficiency**: Optimized stack usage for move tracking
- **Algorithm Implementation**: Complex puzzle generation in pure Assembly
- **Input Validation**: Comprehensive rule checking without external libraries
- **Interactive Interface**: Real-time keyboard input processing

## 🚀 Performance

- **Fast Execution**: Direct hardware interaction via Assembly
- **Low Memory Footprint**: Efficient memory management
- **Instant Response**: Real-time input validation and feedback

## 🤝 Contributing

Contributions are welcome! Areas for enhancement:
- Additional puzzle difficulty levels
- Save/load game functionality  
- Hint system implementation
- Enhanced visual interface
- Timer functionality

## 📝 Development Notes

This project demonstrates advanced Assembly programming concepts:
- Stack manipulation for data structures
- Complex algorithm implementation
- User interface handling in Assembly
- Memory management techniques
- Input validation and error handling

## 📄 License

This project is open source. Feel free to use, modify, and distribute according to your needs.

## 🎓 Educational Value

Perfect for learning:
- x86 Assembly programming
- Algorithm implementation in low-level languages
- Stack-based data structures
- Game logic programming
- Console interface development

---

**Enjoy playing and learning with SudokuASM!** 🧩

*Built with passion for Assembly programming and puzzle games.*
