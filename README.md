# 🐍 Snake Game - Classic Arcade Game

A fully functional, browser-based Snake game built with modern web technologies. This classic arcade game features smooth controls, increasing difficulty, and a polished user interface.

![Snake Game Preview](https://img.shields.io/badge/Game-Snake-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## 🎮 Live Demo

You can play the game directly by opening `snake-game.html` in your web browser, or use the static server:

```bash
# Start the static server (if not already running)
python3 -m http.server 8080
```

Then open: `http://localhost:8080/snake-game.html`

## 📁 Project Structure

```
hello-world/
├── snake-game.html          # Main game file
├── SNAKE_GAME_README.md     # Detailed game documentation
├── SERVER_INFO.md           # Server setup instructions
├── README.md                # This file
└── .git/                    # Git repository
```

## ✨ Features

### 🎯 Core Gameplay
- **Classic Snake Mechanics**: Control a snake that grows as it eats food
- **Score System**: Earn 10 points for each food item
- **Increasing Difficulty**: Game speed increases as your score goes up
- **Game Over Detection**: Collision detection for walls and self-collision

### 🎨 User Interface
- **Responsive Design**: Works on desktop and mobile devices
- **Dark Theme**: Easy-on-the-eyes dark color scheme
- **Visual Feedback**: Clear game states (playing, paused, game over)
- **Score Display**: Real-time score tracking

### ⚙️ Controls & Options
- **Dual Control Schemes**: Arrow Keys (↑↓←→) and WASD keys
- **Game Controls**:
  - Start Game: Begin a new game
  - Pause/Resume: Toggle game state
  - Reset Game: Restart from scratch
- **Game States**: Playing, Paused, Game Over

### 🔧 Technical Features
- **HTML5 Canvas**: Smooth rendering and animation
- **Vanilla JavaScript**: No external dependencies
- **CSS3 Animations**: Polished visual effects
- **Modular Code**: Well-organized, commented source code

## 🚀 Quick Start

### Option 1: Direct File Access
1. Clone the repository:
   ```bash
   git clone https://github.com/zhaozq2/hello-world.git
   ```
2. Open `snake-game.html` in any modern web browser

### Option 2: Static Server
1. Navigate to the project directory:
   ```bash
   cd hello-world
   ```
2. Start a static HTTP server:
   ```bash
   python3 -m http.server 8080
   ```
3. Open your browser and visit:
   ```
   http://localhost:8080/snake-game.html
   ```

## 🎯 How to Play

1. **Start the Game**: Click the "Start Game" button
2. **Control the Snake**:
   - Use **Arrow Keys** (↑, ↓, ←, →) or **WASD** keys
   - The snake moves continuously in the selected direction
3. **Eat Food**: Guide the snake to eat the red food items
4. **Grow & Score**: Each food item:
   - Increases your score by 10 points
   - Makes the snake grow longer
   - Gradually increases game speed
5. **Avoid Obstacles**:
   - Don't hit the walls
   - Don't run into yourself
6. **Game Controls**:
   - **Pause**: Click "Pause" or press Spacebar (future feature)
   - **Reset**: Click "Reset Game" to start over

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Game structure and canvas element |
| **CSS3** | Styling, animations, and responsive design |
| **JavaScript** | Game logic, controls, and interactivity |
| **HTML5 Canvas** | Game rendering and graphics |
| **Git** | Version control and collaboration |

## 📖 Game Rules

1. **Objective**: Eat as much food as possible without dying
2. **Scoring**: 10 points per food item
3. **Speed Increase**: Game gets faster every 50 points
4. **Game Over Conditions**:
   - Snake hits the wall
   - Snake collides with itself
5. **Controls**: Arrow Keys or WASD for movement

## 🌐 Browser Compatibility

The game works on all modern browsers:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Opera 50+

**Requirements**: Modern browser with JavaScript enabled

## 🔍 Code Overview

The game is implemented in a single HTML file with three main sections:

1. **HTML Structure**: Game canvas and UI elements
2. **CSS Styling**: Responsive design and visual effects
3. **JavaScript Logic**:
   - Game state management
   - Snake movement and collision detection
   - Food generation and scoring
   - User input handling
   - Canvas rendering

## 📈 Future Enhancements

Potential features for future versions:
- [ ] High score tracking with localStorage
- [ ] Different difficulty levels
- [ ] Sound effects and background music
- [ ] Mobile touch controls
- [ ] Power-ups and special food types
- [ ] Multiple snake skins/themes
- [ ] Online leaderboard

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements!

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic Nokia Snake game
- Built as a demonstration of modern web technologies
- Thanks to all open-source contributors

---

**Enjoy the game!** 🐍🎮

*If you encounter any issues or have suggestions, please open an issue on GitHub.*
