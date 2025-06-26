# Tenzies

A React-based implementation of the Tenzies dice game, demonstrating fundamental React concepts such as state management, component composition, and accessibility best practices.

## Features

- Roll 10 dice and try to get all the same value.
- Click a die to "hold" its value between rolls.
- Confetti animation and accessible announcement when you win.
- Responsive and visually appealing UI.

## Live Demo

Try the game live: [tenziesnitin.netlify.app](https://tenziesnitin.netlify.app/)

## Project Structure

- [`App.jsx`](App.jsx): Main game logic and UI.
- [`Die.jsx`](Die.jsx): Individual die component.
- [`index.jsx`](index.jsx): Entry point, renders the app.
- [`index.css`](index.css): Styles for the app.
- [`index.html`](index.html): HTML template.
- [`vite.config.js`](vite.config.js): Vite configuration.
- [`package.json`](package.json): Project dependencies and scripts.

## Getting Started

1. **Install dependencies:**
    ```sh
    npm install
    ```

2. **Run the development server:**
    ```sh
    npm start
    ```

3. **Build for production:**
    ```sh
    npm run build
    ```

## Accessibility

- Uses ARIA attributes for better screen reader support.
- Focus is managed for the "New Game" button after winning.

## Credits

- Built after following a React course on Scrimba.
- Confetti animation via [`react-confetti`](https://www.npmjs.com/package/react-confetti).
- Unique IDs via [`nanoid`](https://www.npmjs.com/package/nanoid).

---