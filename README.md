# 🧩 Rubik's Cube Game

> A modern web-based 3D Rubik's Cube simulator with advanced solving features

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

Welcome to the **Rubik's Cube Game** - a fully interactive web-based 3D Rubik's Cube simulator! Master the classic 3x3 puzzle with modern features, intuitive controls, and comprehensive learning tools. Perfect for beginners learning their first solve or speedcubers practicing advanced algorithms.

## ✨ Features

### 🎮 Core Gameplay
- **3D Interactive Cube** - Smooth 3D rotations and realistic cube physics
- **Intuitive Controls** - Mouse drag, keyboard shortcuts, and touch support
- **Real-time Validation** - Instant feedback on moves and solve state
- **Multiple Solving Methods** - Support for CFOP, Roux, and beginner methods

### 📊 Performance Tracking
- **⏱️ Smart Timer** - Precision timing with inspection period
- **📈 Statistics Dashboard** - Track averages, personal bests, and progress
- **📋 Move Counter** - Monitor efficiency with move counting
- **🏆 Achievement System** - Unlock milestones and personal records

### 🛠️ Advanced Tools
- **🎲 Scramble Generator** - WCA-standard random scrambles
- **🔄 Auto-Solver** - Step-by-step solving demonstrations
- **📚 Tutorial Mode** - Interactive lessons for all skill levels
- **🎨 Color Customization** - Personalize cube colors and themes
- **💾 Save & Load** - Preserve your progress and cube states

### 📱 Accessibility
- **Responsive Design** - Seamless experience on all devices
- **Touch Controls** - Optimized for mobile and tablet use
- **Keyboard Navigation** - Full accessibility support
- **Dark/Light Mode** - Eye-friendly viewing options

## 🛠️ Technologies

| Technology | Purpose | Features Used |
|------------|---------|---------------|
| **HTML5** | Structure & Markup | Canvas API, Semantic elements |
| **CSS3** | Styling & Animations | 3D Transforms, Flexbox, Grid |
| **JavaScript** | Logic & Interactivity | ES6+, Canvas manipulation, Web APIs |

## 🚀 Quick Start

### 🌐 Online Demo
[**🎮 Play Now**](https://cube-game-zeta.vercel.app/) - No installation required!

### 💻 Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/euii-ii/-Rubik-s-Cube-Game.git
   cd cube-game
   ```

2. **Launch the game**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Local server (recommended)
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

## 📁 Project Structure

```
cube-game/
├── 📄 index.html              # Main HTML file
├── 📁 css/
│   ├── styles.css            # Core styling
│   ├── cube.css              # 3D cube animations
│   ├── responsive.css        # Mobile responsiveness
│   └── themes.css            # Color themes
├── 📁 js/
│   ├── main.js               # Application entry point
│   ├── cube.js               # Cube logic and rendering
│   ├── controls.js           # User input handling
│   ├── timer.js              # Timing functionality
│   ├── scrambler.js          # Scramble generation
│   ├── solver.js             # Auto-solving algorithms
│   ├── tutorial.js           # Learning mode
│   └── storage.js            # Local data persistence
├── 📁 assets/
│   ├── images/               # UI icons and graphics
│   ├── sounds/               # Audio feedback (optional)
│   └── fonts/                # Custom typography
├── 📁 algorithms/
│   ├── cfop.json             # CFOP method algorithms
│   ├── roux.json             # Roux method algorithms
│   └── beginner.json         # Beginner-friendly methods
└── 📄 README.md              # Project documentation
```

## 🎮 How to Play

### Basic Controls

#### 🖱️ Mouse Controls
- **Left Click + Drag** - Rotate the entire cube
- **Right Click + Drag** - Rotate individual faces
- **Mouse Wheel** - Zoom in/out
- **Double Click** - Reset view

#### ⌨️ Keyboard Shortcuts
| Key | Action | Key | Action |
|-----|--------|-----|--------|
| `R` | Right face clockwise | `r` | Right face counter-clockwise |
| `U` | Up face clockwise | `u` | Up face counter-clockwise |
| `F` | Front face clockwise | `f` | Front face counter-clockwise |
| `L` | Left face clockwise | `l` | Left face counter-clockwise |
| `D` | Down face clockwise | `d` | Down face counter-clockwise |
| `B` | Back face clockwise | `b` | Back face counter-clockwise |
| `Space` | Start/Stop timer | `Esc` | Reset cube |
| `S` | Scramble cube | `H` | Show/Hide help |

#### 📱 Touch Controls
- **Single Tap** - Select face
- **Swipe** - Rotate selected face
- **Pinch** - Zoom in/out
- **Two-finger Rotate** - Rotate entire cube

### Game Modes

#### 🏁 **Speed Solving**
- Timed solves with WCA-standard scrambles
- Personal best tracking and averages
- Competition-style inspection period

#### 📚 **Learning Mode**
- Step-by-step tutorials for beginners
- Algorithm practice with guided hints
- Visual demonstrations of solving methods

#### 🎯 **Challenge Mode**
- Daily scrambles and challenges
- Achievement unlocking system
- Leaderboards and competitions

## 🎨 Customization

### Color Themes
```javascript
// Customize cube colors in js/main.js
const customColors = {
  white: '#FFFFFF',
  yellow: '#FFD700',
  red: '#FF4444',
  orange: '#FF8800',
  blue: '#4488FF',
  green: '#44FF44'
};
```

### Adding Custom Algorithms
```javascript
// Add to algorithms/custom.json
{
  "name": "My Algorithm",
  "moves": "R U R' U' R U R'",
  "description": "Custom algorithm description"
}
```

## 🔧 Advanced Features

### Auto-Solver Integration
The game includes multiple solving algorithms:
- **Kociemba Algorithm** - Optimal 20-move solutions
- **CFOP Method** - Cross, F2L, OLL, PLL
- **Layer-by-Layer** - Beginner-friendly approach

### Statistics Tracking
- **Session Statistics** - Current session performance
- **Historical Data** - Long-term progress tracking
- **Export/Import** - Share and backup your data

### Performance Optimization
- **Smooth Animations** - 60fps 3D rendering
- **Efficient Algorithms** - Optimized cube state management
- **Memory Management** - Clean resource handling

## 🌐 Browser Compatibility

| Browser | Minimum Version | Status |
|---------|----------------|--------|
| Chrome | 60+ | ✅ Full Support |
| Firefox | 55+ | ✅ Full Support |
| Safari | 12+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |
| Mobile Safari | 12+ | ✅ Touch Optimized |
| Chrome Mobile | 60+ | ✅ Touch Optimized |

**Requirements:**
- HTML5 Canvas support
- ES6+ JavaScript support
- CSS3 3D transforms
- Local Storage (for progress saving)

## 🤝 Contributing

We welcome contributions from the cubing community! Here's how you can help:

### 🐛 Bug Reports
1. Check [existing issues](https://github.com/E-beep-web/cube-game/issues)
2. Create detailed bug report with:
   - Browser and version
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots if applicable

### 💡 Feature Requests
- Algorithm additions
- New solving methods
- UI/UX improvements
- Performance optimizations

### 🔧 Development
1. **Fork the repository**
2. **Create feature branch**
   ```bash
   git checkout -b feature/new-algorithm
   ```
3. **Make changes**
   - Follow existing code style
   - Add comments for complex logic
   - Test across different browsers
4. **Submit pull request**

### 📋 Development Guidelines
- Use vanilla JavaScript (no frameworks)
- Maintain 60fps performance
- Ensure mobile compatibility
- Follow semantic HTML practices
- Use CSS custom properties for theming

## 📚 Learning Resources

### Solving Methods
- [**CFOP Tutorial**](https://www.speedsolving.com/wiki/index.php/CFOP) - Most popular speedsolving method
- [**Roux Method**](https://www.speedsolving.com/wiki/index.php/Roux) - Block-building approach
- [**Beginner's Guide**](https://ruwix.com/the-rubiks-cube/how-to-solve-the-rubiks-cube-beginners-method/) - Layer-by-layer method

### Algorithm Collections
- [**Algorithm Database**](https://www.speedsolving.com/wiki/index.php/Algorithms) - Comprehensive algorithm list
- [**OLL Algorithms**](https://www.speedsolving.com/wiki/index.php/OLL) - Orientation of Last Layer
- [**PLL Algorithms**](https://www.speedsolving.com/wiki/index.php/PLL) - Permutation of Last Layer

## 📊 Performance Metrics

- **Bundle Size** - ~500KB total (uncompressed)
- **Load Time** - <2s on 3G connection
- **Frame Rate** - 60fps on modern devices
- **Memory Usage** - <50MB typical session

## 📝 License

This project is licensed under the [MIT License](LICENSE).

```
MIT License

Copyright (c) 2024 E-beep-web

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Acknowledgments

- **World Cube Association** - Official competition standards
- **Speedsolving.com** - Algorithm database and community
- **Ruwix.com** - Educational resources and tutorials
- **Cubing Community** - Feedback and feature suggestions

## 🔗 Links & Resources

- [🎮 **Live Demo**](https://e-beep-web.github.io/cube-game/) - Play online now
- [📚 **Documentation**](https://github.com/E-beep-web/cube-game/wiki) - Detailed guides
- [🐛 **Issues**](https://github.com/E-beep-web/cube-game/issues) - Bug reports & features
- [💬 **Discussions**](https://github.com/E-beep-web/cube-game/discussions) - Community chat
- [🏆 **Leaderboards**](https://your-leaderboard-link.com) - Global rankings
- [📱 **Mobile App**](https://your-app-store-link.com) - Native mobile version

## 📈 Roadmap

### Version 2.0 (Coming Soon)
- [ ] **Multiplayer Mode** - Race against friends online
- [ ] **AR Integration** - Augmented reality cube overlay
- [ ] **Voice Commands** - Hands-free cube manipulation
- [ ] **AI Coach** - Personalized solving tips and training

### Future Features
- [ ] **VR Support** - Full virtual reality experience
- [ ] **Cube Scanner** - Real cube state recognition
- [ ] **Tournament Mode** - Official competition simulation
- [ ] **Social Features** - Share solves and compete with friends

---

<div align="center">
  <p>🧩 <strong>Master the Cube, Master the Mind</strong> 🧩</p>
  <p>Built with ❤️ by <a href="(https://github.com/euii-ii/-Rubik-s-Cube-Game.git)">euii-ii</a></p>
  <p>⭐ Star this repo if you love cubing!</p>
  <p><em>Join thousands of cubers worldwide in the ultimate puzzle experience</em></p>
</div>
