# Memory Game

A responsive and accessible Memory (Concentration) card game built with HTML, CSS, and JavaScript.

## Features

- 4x4 and 6x6 grid options
- Smooth card flip animations
- Timer and moves counter
- Star rating system
- Local storage for best scores
- Keyboard controls for accessibility
- Responsive design for all devices
- No external dependencies
 - Dark mode toggle with system preference support

## How to Play

1. Open `memory-game.html` in a web browser
 1. Use the theme toggle in the top-right to switch between light and dark modes (preference is saved in your browser)
2. Click or use keyboard (Tab + Enter/Space) to flip cards
3. Find matching pairs to win
4. Try to complete the game with as few moves as possible
5. Switch between 4x4 and 6x6 grids using the buttons

## Technical Details

- Pure HTML, CSS, and JavaScript implementation
- No external libraries or dependencies
- Fully responsive design using CSS Grid
- Accessible with ARIA attributes and keyboard controls
- Local storage for persistent high scores

## Development

1. Clone the repository
2. Open `memory-game.html` in a web browser
3. Or serve using a local HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
4. Visit `http://localhost:8000/memory-game.html`