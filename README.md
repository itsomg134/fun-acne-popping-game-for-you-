# fun-acne-popping-game-for-you-

# 🎯 Acne Popping Game

A fun and satisfying browser-based game where you pop acne spots against the clock! Test your reflexes and aim for the high score in this oddly satisfying clicking game.

![Game Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎮 Play Now

[Live Demo](your-github-pages-url-here) _(Add your GitHub Pages link)_

## 📸 Screenshot

![Acne Popping Game Screenshot](screenshot.png) _(Add a screenshot of your game)_

## ✨ Features

- **Three Difficulty Levels**: Small, medium, and large acne spots with varying point values
- **Progressive Difficulty**: Game speeds up as you level up
- **Time Extensions**: Earn extra time by reaching new levels
- **Satisfying Animations**: Pop effects and score splashes for visual feedback
- **Responsive Design**: Works on desktop and mobile devices
- **Score Tracking**: Real-time score, timer, and level display
- **No Dependencies**: Pure vanilla HTML, CSS, and JavaScript

## 🎯 Game Mechanics

### Scoring System
- **Small Acne** (Red): 10 points
- **Medium Acne** (Darker Red): 20 points
- **Large Acne** (Deep Red): 30 points

### Gameplay
- Starting time: 60 seconds
- Acne spots disappear after 3 seconds
- Level up every 200 points
- Gain 10 bonus seconds per level
- Spawn rate increases with each level

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required!

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/acne-popping-game.git
```

2. Navigate to the project directory
```bash
cd acne-popping-game
```

3. Open `index.html` in your browser
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or simply double-click the `index.html` file!

## 📁 Project Structure

```
acne-popping-game/
│
├── index.html          # Main game file (complete standalone game)
├── README.md           # Project documentation
├── LICENSE             # License file
└── screenshot.png      # Game screenshot (optional)
```

## 🎨 Customization

The game is built with clean, well-commented code that's easy to customize:

### Adjust Difficulty
```javascript
// Change spawn intervals (line ~100)
spawnInterval = setInterval(spawnAcne, 1500); // milliseconds

// Modify acne lifespan (line ~125)
setTimeout(() => {
    if (acne.parentNode) {
        acne.remove();
    }
}, 3000); // milliseconds
```

### Change Scoring
```javascript
// Update point values (line ~107)
const points = [10, 20, 30]; // Small, Medium, Large
```

### Modify Timer
```javascript
// Change starting time (line ~47)
let timeLeft = 60; // seconds

// Adjust bonus time per level (line ~168)
timeLeft += 10; // seconds
```

## 🛠️ Technologies Used

- **HTML5**: Structure and semantics
- **CSS3**: Styling, animations, and responsive design
  - Flexbox for layout
  - CSS animations for visual effects
  - Gradients and shadows for depth
- **Vanilla JavaScript**: Game logic and interactivity
  - No frameworks or libraries
  - ES6+ features

## 🌟 Future Enhancements

- [ ] Add sound effects for popping
- [ ] Implement high score leaderboard with localStorage
- [ ] Add different game modes (zen mode, endless mode)
- [ ] Include power-ups (freeze time, multi-pop, score multiplier)
- [ ] Add difficulty selection (easy, medium, hard)
- [ ] Mobile touch optimization
- [ ] Add achievements and badges
- [ ] Implement combo system for consecutive pops

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by satisfying mobile games
- Built as a fun JavaScript practice project
- Thanks to the open-source community for inspiration

## 📊 Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome  | ✅ Yes    |
| Firefox | ✅ Yes    |
| Safari  | ✅ Yes    |
| Edge    | ✅ Yes    |
| Opera   | ✅ Yes    |

## 🐛 Known Issues

None currently! If you find a bug, please [open an issue](https://github.com/yourusername/acne-popping-game
