# Pong Game 🎮

A classic Pong game built with HTML5, CSS3, and Vanilla JavaScript. Play against an intelligent computer opponent!

## Features

✨ **Player Controls**
- Move your paddle with mouse (smooth tracking)
- Or use arrow keys (↑/↓) for precise control

🤖 **Computer AI**
- Intelligent opponent that adapts to ball movement
- Adjustable difficulty through AI speed

⚽ **Physics Engine**
- Realistic ball bouncing with wall collisions
- Ball spin based on paddle hit location
- Smooth paddle movement and collision detection

📊 **Game Features**
- Real-time scoreboard
- Win condition (First to 5 points)
- Responsive design for different screen sizes
- Modern neon-styled UI

## How to Play

1. Open `index.html` in your web browser
2. Move your paddle (left side) using your mouse or arrow keys
3. Try to score 5 points before the computer does
4. The ball bounces off paddles and walls
5. If the ball passes your paddle, the computer scores

## Game Rules

- Each player has one paddle
- The ball bounces off top and bottom walls
- If a player misses the ball, the opponent scores
- First player to reach 5 points wins
- After a point is scored, the ball resets to center

## Controls

| Action | Key |
|--------|-----|
| Move Up | Mouse Up / ↑ Arrow |
| Move Down | Mouse Down / ↓ Arrow |

## File Structure

```
pong-game/
├── index.html      # Main HTML file with canvas and UI
├── style.css       # Styling and responsive design
├── game.js         # Game logic and physics engine
└── README.md       # This file
```

## Technical Details

### Game Objects
- **Player Paddle**: Left side, controlled by player
- **Computer Paddle**: Right side, controlled by AI
- **Ball**: Center, bounces around the canvas

### Physics
- Ball-wall collision detection
- Ball-paddle collision detection with spin mechanics
- Smooth paddle movement with boundaries

### AI Algorithm
- Simple but effective: follows ball Y-position
- Slightly slower than player for balanced gameplay

## Customization

You can adjust difficulty by modifying values in `game.js`:

```javascript
// Change computer speed (default: 4)
computer.speed = 5;  // Higher = harder

// Change player speed (default: 6)
player.speed = 7;    // Higher = faster

// Change win score (default: 5)
const winScore = 10; // Play longer games
```

## Browser Compatibility

- Chrome ✅
- Firefox ✅
- Safari ✅
- Edge ✅
- Modern browsers with HTML5 Canvas support

## License

Free to use and modify!

Enjoy the game! 🎮