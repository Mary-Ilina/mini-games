# Mini Games

A small, dependency-free collection of browser mini-games. Plain HTML/CSS/JS, no build step.

Live site: https://mary-ilina.github.io/mini-games/

## Games

- Snake (`games/snake/`) — classic grid snake, arrow keys or WASD.
- Snake 3D (`games/snake-3d/`) — snake in a rendered 3D cube, arrow keys + W/S to move, drag/A/D/Q/E to orbit.

## Adding a new game

Add a subfolder `games/<name>/index.html` for the game, then add one matching card to the grid in the root `index.html` linking to it.
