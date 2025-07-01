# 🐜 Ant Smasher Game

A modern, interactive Ant Smasher game built with HTML, CSS, and JavaScript. Smash ants and special insects to earn points in this engaging web-based arcade game with smooth animations, sound effects, and bonus features!

---

## 🚀 Live Preview

Try the game instantly:  
👉 [Play Ant Smasher Online](https://sonseldeep.github.io/Ant-Smasher-Game/)

---

## ✨ Features

### 🎮 **Core Gameplay**

- **Smooth Ant Spawning:** Ants appear randomly across the screen with realistic animations
- **Special Bonus Insects:** High-value targets that give extra points
- **Progressive Difficulty:** Game speed increases over time for added challenge
- **Score System:** Real-time score tracking with milestone celebrations

### 🐛 **Insect Types & Points**

- **🐜 Regular Ants:** 1 point each
- **🦗 Cricket:** 3 points (appears in center area)
- **🐛 Caterpillar:** 5 points (appears in center area)
- **🕷️ Spider:** 7 points (appears in center area)
- **🪲 Beetle:** 10 points (highest value, appears in center area)

### 🎨 **Visual & Audio**

- **Modern Glassmorphism UI:** Clean, professional interface with blur effects
- **Particle Effects:** Colorful explosions when insects are smashed
- **Sound Effects:** Programmatic audio for smashing, spawning, and game events
- **Smooth Animations:** CSS-based transitions and hover effects
- **Responsive Design:** Works perfectly on desktop and mobile devices

### 🏆 **Game Features**

- **High Score Tracking:** Persistent high scores using localStorage
- **Pause/Resume:** Game can be paused at any time
- **Game Statistics:** Track time played and missed insects
- **Milestone Rewards:** Celebration messages for score milestones
- **Keyboard Shortcuts:** Space for pause/resume, R for restart

---

## 🛠️ Technologies Used

- **HTML5** - Semantic structure and game layout
- **CSS3** - Modern styling with glassmorphism effects, animations, and responsive design
- **Vanilla JavaScript** - Game logic, DOM manipulation, and Web Audio API
- **LocalStorage** - Persistent high score tracking
- **Web Audio API** - Programmatic sound effects

---

> **Assignment:** This project was created as part of the LSpp - JavaScript session assignment.

---

## 🚀 Getting Started

### **Method 1: Download & Play**

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Sonseldeep/lspp-ant-smasher
   cd lspp-ant-smasher
   ```

2. **Open the Game**

   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):

   ```bash
   # Using Python
   python -m http.server 8080

   # Using Node.js
   npx serve .
   ```

   Then visit `http://localhost:8080`

### **Method 2: Live Server (VS Code)**

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"

---

## 🎮 How to Play

### **Basic Gameplay**

1. **Start the Game:** Click the "Start Game" button or press `Space`
2. **Smash Insects:** Click on any insect that appears on screen
3. **Earn Points:** Different insects give different point values
4. **Beat Your High Score:** Try to achieve the highest score possible!

### **Controls**

- **🖱️ Mouse Click:** Smash insects
- **⌨️ Spacebar:** Start game / Pause & Resume
- **⌨️ R Key:** Restart game
- **🔘 Pause Button:** Pause/Resume gameplay
- **🔄 Restart Button:** Reset game to beginning

### **Scoring System**

- **🐜 Regular Ants:** 1 point each (most common)
- **🦗 Cricket:** 3 points (appears after 10 seconds)
- **🐛 Caterpillar:** 5 points (appears after 10 seconds)
- **🕷️ Spider:** 7 points (appears after 10 seconds)
- **🪲 Beetle:** 10 points (rarest, highest value)

### **Strategy Tips**

- Focus on high-value insects in the center area
- Special insects stay longer but are worth more points
- Don't miss too many - keep your accuracy high!
- Game gets faster over time, so stay alert!

---

## 🏆 Game Features & Mechanics

### **Visual Effects**

- **Glassmorphism UI:** Modern, translucent design with backdrop blur
- **Particle Explosions:** Colorful particles burst when insects are smashed
- **Smooth Animations:** CSS-powered transitions and hover effects
- **Score Popups:** Dynamic point notifications with special effects
- **Milestone Celebrations:** Congratulatory messages for score achievements

### **Audio System**

- **Smash Sounds:** Satisfying audio feedback when hitting insects
- **Spawn Sounds:** Subtle audio cues when insects appear
- **Game Start/Over:** Musical chords for game state changes
- **Web Audio API:** Programmatically generated sound effects

### **Game Progression**

- **Adaptive Difficulty:** Spawn rate increases every 10 seconds
- **Special Insect Timing:** Bonus insects appear after 10 seconds of gameplay
- **Center Spawning:** High-value insects appear more frequently in center area
- **Extended Lifespan:** Special insects stay 6-9 seconds vs regular ants' 4-6 seconds

### **Data Persistence**

- **High Score Tracking:** Best score saved automatically using localStorage
- **Cross-Session Memory:** High scores persist between browser sessions
- **Real-time Updates:** Score displays update with smooth animations

---

## 📋 System Requirements

### **Minimum Requirements**

- **Browser:** Modern web browser with JavaScript enabled
  - Chrome 60+ (recommended)
  - Firefox 60+
  - Safari 12+
  - Edge 79+
- **Audio:** Web Audio API support (for sound effects)
- **Storage:** ~1MB local storage space for high scores
- **Screen:** 1024x768 minimum resolution

### **Recommended**

- **Browser:** Latest version of Chrome or Firefox
- **Audio:** Speakers or headphones for full experience
- **Input:** Mouse or touchscreen for optimal gameplay

---

## 🎯 Project Structure

```
lspp-ant-smasher/
├── index.html          # Main game page with semantic HTML
├── style.css          # Modern CSS with glassmorphism and animations
├── script.js          # Game logic and Web Audio API implementation
└── readme.md          # Project documentation
```

## ✨ Customization & Extension Ideas

### **Easy Modifications**

- **Insect Types:** Add new emoji insects with custom point values
- **Colors:** Modify CSS color schemes in `style.css`
- **Spawn Rates:** Adjust timing intervals in `script.js`
- **Sound Effects:** Customize audio frequencies in sound creation methods

### **Advanced Features to Add**

- **Power-ups:** Temporary abilities like slow motion or double points
- **Levels:** Different backgrounds and difficulty tiers
- **Multiplayer:** Real-time competition between players
- **Leaderboards:** Global score tracking with backend integration
- **Mobile Controls:** Touch gesture support for mobile devices

## 🐛 Known Issues & Solutions

- **Audio on Mobile:** Some mobile browsers require user interaction before playing audio
- **Performance:** Reduce particle count if experiencing lag on older devices
- **Storage:** Game will work without localStorage but won't save high scores

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements! Areas for contribution:

- Performance optimizations
- New visual effects
- Additional insect types
- Mobile responsiveness improvements
- Accessibility features

---

## � Screenshots

_Game features a modern glassmorphism UI with smooth animations and particle effects_

## 🏅 Achievements Unlocked

This project demonstrates proficiency in:

- ✅ **Vanilla JavaScript:** Complex game logic without frameworks
- ✅ **Modern CSS:** Glassmorphism, animations, and responsive design
- ✅ **Web Audio API:** Programmatic sound generation
- ✅ **DOM Manipulation:** Dynamic content creation and management
- ✅ **Local Storage:** Data persistence across sessions
- ✅ **Event Handling:** Mouse, keyboard, and touch interactions
- ✅ **Game Development:** Spawn systems, collision detection, scoring
- ✅ **UX Design:** Intuitive controls and visual feedback

## �📄 License

This project is created for educational purposes as part of the LSpp JavaScript assignment.

---

## 🎮 Start Playing!

Ready to test your reflexes? Launch the game and see how many insects you can smash!

**Challenge yourself:**

- Can you reach 100 points?
- What's the highest combo you can achieve?
- How long can you survive as the game speeds up?

---

_Enjoy smashing insects and climbing the leaderboard! 🐜🎯_
