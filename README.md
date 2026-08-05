# Mini Games

A small, dependency-free collection of browser mini-games. Plain HTML/CSS/JS, no build step.

Live site: https://mary-ilina.github.io/mini-games/

## Games

- Snake (`games/snake/`) — classic grid snake, arrow keys or WASD.
- Snake 3D (`games/snake-3d/`) — snake on a flat, slightly tilted board rendered as 3D-shaded blocks, arrow keys or WASD to move, space to restart.

## Adding a new game

Add a subfolder `games/<name>/index.html` for the game, then add one matching card to the grid in the root `index.html` linking to it.
