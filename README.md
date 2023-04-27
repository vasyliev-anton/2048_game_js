# [Demo](https://vasyliev-anton.github.io/js_2048_game/)

# The game employs a specific game logic:
- The game field consists of 16 cells arranged in a 4 x 4 grid, but its size can be easily customized in the code.
- When the player moves the cells, all the numbers are shifted in the selected direction until all empty cells are filled.
- At the start of the game, two random cells are filled with either 2 or 4.
- The game is initiated by clicking the Start button, and the player can move the cells using the arrow keys.
- If two adjacent cells contain equal numbers, they merge into a single cell with their sum, provided that the merged cell has not already merged during the same move.
- If the number 2048 is displayed in any cell, the game displays a win message.
- Each cell can be either empty or contain a power of 2 number, from 2 up to 2^n.
- After each move, a new number (either 2 or 4) appears in a random empty cell, with a 10% probability of it being 4.
- If there are no more available moves, the game ends and shows a game over message.
- The score increases by the sum of all merged cells, and the high score is saved in the local storage.
- The game can be restarted at any time by clicking the Restart button.

# Technologies used

- HTML5
- CSS3
- Sass (SCSS)
- JavaScript

# General

The primary purpose of this project was to practice JavaScript and DOM manipulations, as well as integrating JavaScript with HTML and CSS. The biggest task was the execution of the game logic. I needed to consider all feasible circumstances and how to apply them.

![Preview](./src/images/reference.png)
