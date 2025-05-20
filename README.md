# 🎲 Dice Game (2-Player Turn-Based)

This is a **two-player dice game** built with vanilla JavaScript. Players take turns rolling a dice, trying to be the first to reach a target score (default: 5 points for demo purposes). If a player rolls a 1, they lose their current score and it's the next player's turn.

## 🕹️ How to Play

1. **Roll Dice**: Click the **"Roll Dice"** button to roll a die.
2. If the result is **not 1**, the number is added to your current score.
3. If the result **is 1**, your current score is lost and the turn goes to the other player.
4. **Hold**: Click the **"Hold"** button to save your current score and pass the turn.
5. First player to reach **5 points** wins! (You can change this to 100 later.)

## 🚀 Features

- 🎲 Dice roll logic with random number generation
- 🔁 Turn-based switching between two players
- ⛔ Lose your turn if you roll a 1
- ✅ Hold your score to secure it
- 🏆 Winning screen with player highlight
- 🔄 Restart the game anytime with the **"New Game"** button

## 🧠 With This, I Learned

- DOM manipulation (`getElementById`, `querySelector`)
- Event handling with `.addEventListener()`
- Game logic with conditionals and functions
- Toggling classes (`classList.toggle`, `add`, `remove`)
- Managing game state using variables (`scores`, `activePlayer`, `playing`)

## 🗂️ Files

- `index.html`: HTML structure for the game board and UI
- `style.css`: Styles for layout, colors, active/winner highlights
- `script.js`: Game logic using vanilla JavaScript

## 📦 How to Run

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. Play the game by clicking the buttons!
