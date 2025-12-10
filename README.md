# 🎮 Simon Game

A web-based implementation of the classic electronic memory game, **Simon**. Test your memory by repeating sequences of colors and sounds that get progressively longer and faster!

## ✨ Features

* **Interactive Gameplay:** Users click colored buttons to match the generated sequence.
* **Audio Feedback:** Distinct sounds for each color (Red, Blue, Green, Yellow) and a specific sound for wrong answers.
* **Visual Effects:** Button animations when pressed and a red background flash upon "Game Over".
* **Level Tracking:** The game tracks your current level, updating the title dynamically.
* **Restart Function:** Seamlessly restart the game after a loss by pressing any key.

## 🕹️ How to Play

1.  **Start the Game:** Open the page and press **any key** on your keyboard to begin. The title will change to "Level 1".
2.  **Watch the Pattern:** The game will flash a button and play a sound.
3.  **Repeat the Pattern:** Click the buttons in the exact order shown by the game.
4.  **Level Up:** If you get the sequence right, the game adds a new step to the pattern and you advance to the next level.
5.  **Game Over:** If you click the wrong button, the game ends, the screen flashes red, and a "Wrong" sound plays. Press any key to restart.

## 🛠️ Technologies Used

* **HTML5:** Structure of the game board.
* **CSS3:** Styling, grid layout, and animations.
* **JavaScript:** Game logic, sequence generation, and state management.
* **jQuery:** Used for DOM manipulation and event handling.
* **Fonts:** Uses the "Press Start 2P" font from Google Fonts for a retro arcade look.

## 📂 Project Structure

```text
├── index.html      # Main game interface
├── styles.css      # Game styling
├── game.js         # Game logic and behavior
└── sounds/         # Audio files
    ├── blue.mp3
    ├── green.mp3
    ├── red.mp3
    ├── yellow.mp3
    └── wrong.mp3
