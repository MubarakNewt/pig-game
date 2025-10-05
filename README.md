# Pig Game 🐷🎲

A classic dice game built with vanilla HTML, CSS, and JavaScript. This is a two-player game where players take turns rolling dice to accumulate points, with the goal of reaching 100 points first.

## 🎮 How to Play

### Game Rules

1. **Two players** take turns rolling a single die
2. **Roll the dice**: Each roll adds to your current score
3. **Hold**: Add your current score to your total score and pass the turn
4. **Roll a 1**: Lose all current score and pass the turn to the other player
5. **Win**: First player to reach **100 points** wins!

### Game Controls

- **🎲 Roll dice**: Roll the die and add to current score
- **📥 Hold**: Save current score and pass turn to other player
- **🔄 New game**: Start a fresh game

## 🎯 Strategy Tips

- **Risk vs Reward**: The longer you roll, the higher your current score, but rolling a 1 loses everything
- **Know when to hold**: Don't get too greedy - sometimes it's better to secure points than risk losing them
- **Watch your opponent**: If they're close to winning, you might need to take bigger risks

## 🛠️ Technical Details

### Files Structure

```
pig-game/
├── index.html          # Main HTML structure
├── script.js           # Game logic and functionality
├── style.css           # Styling and layout
├── dice-1.png to dice-6.png  # Dice face images
└── pig-game-flowchart.png    # Game flow diagram
```

### Key Features

- **Responsive Design**: Clean, modern UI with glassmorphism effects
- **Real-time Updates**: Instant score updates and player switching
- **Visual Feedback**: Active player highlighting and winner celebration
- **Smooth Animations**: CSS transitions for better user experience

### Game State Management

The game tracks:

- `scores[]`: Total scores for both players
- `currentScore`: Points accumulated in current turn
- `activePlayer`: Which player's turn it is (0 or 1)
- `playing`: Whether the game is still active

## 🚀 Getting Started

1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **Start playing** immediately - no installation required!

## 🎨 Design Features

- **Glassmorphism UI**: Modern frosted glass effect with backdrop blur
- **Gradient Background**: Beautiful purple-to-red gradient
- **Custom Font**: Nunito font family for clean typography
- **Smooth Animations**: CSS transitions for all interactions
- **Visual Hierarchy**: Clear distinction between active/inactive players

## 🏆 Game Mechanics

### Turn Flow

1. Player clicks "Roll dice"
2. Die shows random number (1-6)
3. If not 1: Add to current score
4. If 1: Lose current score, switch players
5. Player can "Hold" to save current score
6. Check if player reached 100 points
7. If not, switch to other player

### Win Condition

- First player to reach **100 points** wins
- Game ends immediately when condition is met
- Winner gets highlighted with special styling

## 🔧 Browser Compatibility

- **Modern browsers** (Chrome, Firefox, Safari, Edge)
- **Mobile responsive** design
- **No external dependencies** - pure vanilla JavaScript

## 📱 Mobile Friendly

The game is fully responsive and works great on:

- Desktop computers
- Tablets
- Mobile phones
- Touch devices

---

**Enjoy playing Pig Game! 🎲🐷**
