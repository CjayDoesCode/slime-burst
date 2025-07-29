# Slime Burst

**Slime Burst** is a tile-based strategy game with the goal of dominating the board.

## Rules

1. On initial placement, each player selects an empty tile to place a slime of their color.

2. On player's turn, the active player may choose to increase the size of one of their slimes or place a slime of their color on an empty tile.

3. After player's turn, slimes whose size exceeds their limit will burst. This continues until equilibrium is reached.

4. A player loses if no slimes of their color remain.

4. A player wins if only slimes of their color remain.

## Types of Slimes

| Slime Type   | Size Limit | Burst Effect                                                                                                                                                       |
| :---:        | :---:      | :---                                                                                                                                                               |
| Normal Slime | 3          | Slime fragments are scattered to orthogonally adjacent tiles, dropping a slime on empty tiles or increasing the size and converting the color of  existing slimes. |
| Spiked Slime | 4          | Slime fragments are launched in straight directions, increasing the size and converting the color of slimes hit.                                                   |
| Mother Slime | 5          | Slime fragments are scattered to adjacent tiles, dropping a slime on empty tiles or increasing the size and converting the color of  existing slimes.              |
