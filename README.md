# 2048 Game Implementation

This project is a simple implementation of the 2048 game using HTML, CSS, and JavaScript. The game allows users to combine tiles of the same value to achieve the target score of 2048. If the grid is full and no moves are possible, the game will display a "Try Again" message.

---

## Features

- **Dynamic Grid:** A 4x4 grid where tiles merge when moved in the same direction.
- **Game Over Detection:** Displays a message when the grid is full and no moves are possible.
- **Customizable Overlay:** A styled overlay appears when the game is over.
- **Restart Button:** Allows users to restart the game after losing.

---

## How It Works

### Gameplay
- Use arrow keys to move tiles on the grid.
- Tiles of the same value merge into one when they collide.
- The game ends when the grid is full, and no valid moves remain.

### Loss Condition
When all grid cells are filled and no moves are possible:
- An alert or overlay displays the message: **"Game Over! Try Again!"**
- Players can click the "Restart" button to reload the game.

---

## File Structure

```
|-- index.html
|-- styles.css
|-- script.js
|-- README.md
```

### `index.html`
Contains the basic structure of the game and placeholders for the grid and overlay.

### `styles.css`
Defines styles for the grid, cells, overlay, and game status messages.

### `script.js`
Includes the game logic for tile movement, merging, and loss detection.

---

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in any modern web browser.
3. Use arrow keys to play the game.

---

## Future Enhancements
- Add animations for tile movement and merging.
- Implement scoring and a high-score tracker.
- Introduce additional difficulty levels.
- Make the grid size customizable.

---

## License
This project is open-source and available for anyone to use or modify.

---

## Contact
For questions or suggestions, feel free to reach out:
- **Name:** Akanksha Patil
- **Email:** [akankshapatil2015@gmail.com]
- **Portfolio:** [https://personal-portfolio-rgnrmvqbk-akankshapatil2015s-projects.vercel.app/](https://personal-portfolio-rgnrmvqbk-akankshapatil2015s-projects.vercel.app/)

