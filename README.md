# 🎮 Classic Games Collection

A collection of classic arcade games implemented in Python as part of my programming journey. Each game demonstrates different programming concepts and libraries.

## 🚀 Projects Overview

### 1. 🟡 Pac-Man
**File:** `pacman.py`  
**Library:** Turtle Graphics  
**Description:** A classic Pac-Man game implementation featuring:
- Maze navigation with collision detection
- Ghost AI with random movement patterns
- Dot collection scoring system
- Real-time score display
- Keyboard controls (Arrow keys)

**Key Features:**
- Grid-based movement system
- Dynamic maze rendering
- Multiple ghost entities
- Score tracking and display

### 2. 🐍 Snake Game
**File:** `snake.py`  
**Library:** Pygame  
**Description:** The timeless Snake game with modern implementation:
- Smooth snake movement and growth mechanics
- Food spawning system
- Collision detection (walls and self)
- Score tracking
- Game over handling

**Key Features:**
- 720x480 game window
- Configurable game speed
- Color-coded game elements
- Responsive controls (WASD/Arrow keys)

### 3. ⚡ Tic-Tac-Toe AI
**File:** `tictactoe.py`  
**Library:** Tkinter  
**Description:** An intelligent Tic-Tac-Toe game featuring:
- Unbeatable AI opponent
- Strategic gameplay algorithms
- Clean GUI interface
- Multiple game modes (Human vs AI, AI vs Human)

**Key Features:**
- Advanced AI with multiple strategy techniques
- Dark theme UI
- Win/draw detection
- Game reset functionality

## 🛠️ Installation & Setup

### Prerequisites
Make sure you have Python 3.6+ installed on your system.

### Required Libraries
```bash
# For Snake Game
pip install pygame

# For Pac-Man
pip install freegames

# Tkinter comes pre-installed with Python
```

### Running the Games

**Pac-Man:**
```bash
python pacman.py
```

**Snake:**
```bash
python snake.py
```

**Tic-Tac-Toe:**
```bash
python tictactoe.py
```

## 🎯 Controls

### Pac-Man
- **Arrow Keys:** Move Pac-Man
- **Objective:** Collect all dots while avoiding ghosts

### Snake
- **Arrow Keys / WASD:** Control snake direction
- **Objective:** Eat food to grow while avoiding walls and yourself

### Tic-Tac-Toe
- **Mouse Click:** Place your mark (O)
- **Buttons:** Choose game mode (Human vs AI / AI vs Human)
- **Reset:** Start a new game

## 🧠 Technical Highlights

### Pac-Man Implementation
- **Grid System:** Uses a 20x20 tile-based coordinate system
- **Collision Detection:** Implements boundary checking and ghost proximity detection
- **AI Behavior:** Ghosts use random movement with direction changes on wall collision

### Snake Game Architecture
- **Game Loop:** Implements a proper game loop with FPS control
- **Dynamic Growth:** Snake body grows by adding segments at the tail
- **Boundary Management:** Handles screen wrapping and collision detection

### Tic-Tac-Toe AI Strategy
- **Multi-technique Approach:** Uses different strategies based on game state
- **Defensive Play:** Blocks human winning moves
- **Offensive Play:** Creates winning opportunities
- **Corner Strategy:** Prioritizes corner and center positions

## 📊 Game Statistics

| Game | Lines of Code | Difficulty Level | Key Algorithm |
|------|---------------|------------------|---------------|
| Pac-Man | ~170 | Intermediate | Pathfinding & Collision |
| Snake | ~180 | Beginner | Game Loop & Growth Logic |
| Tic-Tac-Toe | ~400+ | Advanced | Minimax-style AI Strategy |


## 📚 Learning Outcomes

Through these projects, I've gained experience in:
- **Object-Oriented Programming:** Class design and inheritance
- **Game Development:** Game loops, event handling, and state management
- **GUI Programming:** Creating interactive user interfaces
- **Algorithm Design:** Implementing AI logic and game mechanics
- **Problem Solving:** Debugging and optimizing game performance

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements or bug fixes. All contributions are welcome!

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

**GitHub:** [@cipherex](https://github.com/cipherex)

---

*These projects were created as part of my programming education and demonstrate fundamental concepts in Python game development.*
