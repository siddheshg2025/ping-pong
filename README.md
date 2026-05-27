# 🎮 Pong Game

A classic Pong game built with vanilla HTML, CSS, and JavaScript. Play against the computer AI with full collision detection, scoring, and smooth gameplay.

## ✨ Features

✅ **Complete Pong Gameplay**
- Player vs Computer AI
- Smooth paddle and ball physics
- Full collision detection (paddles & walls)
- Ball spin based on paddle hit position
- Real-time scoreboard

🎮 **Player Controls**
- **Arrow Keys (↑/↓)** - Move paddle up/down
- **Mouse** - Move paddle by following your mouse position
- Dual control support for better gameplay

🤖 **Computer AI**
- Intelligent paddle tracking
- Adjustable difficulty
- Realistic opponent behavior

🎨 **Visual Design**
- Retro neon aesthetic with glow effects
- Animated center line
- Responsive layout
- Clean and intuitive UI

## 🎯 Game Rules

- First player to reach **5 points** wins
- Ball bounces off top and bottom walls
- Ball bounces off paddles with directional spin
- Miss the ball → opponent scores
- Win by reaching 5 points first

## 🚀 How to Play

1. **Click here to play:** [https://siddheshg2025.github.io/ping-pong/](https://siddheshg2025.github.io/ping-pong/)
2. Use **Arrow Keys** (↑/↓) or **Mouse** to control your paddle (left side)
3. Keep the ball from getting past your paddle
4. Try to get the ball past the computer's paddle (right side)
5. First to 5 points wins!

## 📁 File Structure

```
ping-pong/
├── index.html    # Main HTML file
├── style.css     # Styling and animations
├── script.js     # Game logic and mechanics
└── README.md     # Documentation
```

## 🔧 Technical Details

### Collision Detection
- **Paddle Collision:** Checks if ball bounds intersect with paddle bounds
- **Wall Collision:** Detects ball contact with top/bottom canvas edges
- **Scoring:** Triggers when ball passes left or right boundary

### Game Physics
- Ball direction changes based on paddle collision point
- Spin applied for more realistic ball behavior
- Ball speed remains constant, direction changes
- Smooth animation using `requestAnimationFrame`

### AI Behavior
- Computer tracks ball Y position
- Moves toward predicted ball location
- Slightly slower than player for balanced gameplay
- Dead zone prevents constant jittering

## 🌐 Browser Compatibility

- Chrome/Chromium ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Any modern browser with HTML5 Canvas support

## 🎮 Live Game

**Play now:** https://siddheshg2025.github.io/ping-pong/

## 🚀 Future Enhancements

- Sound effects
- Difficulty levels
- Two-player mode
- Ball speed increase over time
- Paddle customization
- Score history

## 📄 License

Free to use and modify!

---

**Enjoy the game! 🎉**