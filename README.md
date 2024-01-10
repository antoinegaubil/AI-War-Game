# AI War Game

## Introduction

Welcome to the AI War Game, a Python-based project developed by AI Pros - Alexander Rainbow and Antoine Gaubil. This project is part of COMP472 - Artificial Intelligence at Concordia University, Fall 2023.

## Implementation

### Minimax Algorithm & Alpha-Beta Pruning

In this project, we implemented the minimax algorithm, a crucial element for adversarial search in two-player games. This algorithm explores the game tree, evaluates terminal states, assigns scores based on outcomes, and efficiently backpropagates optimal scores for strategic decision-making. Additionally, we incorporated alpha-beta pruning to optimize efficiency by minimizing unnecessary node evaluations, significantly reducing computation time.

### Heuristics

Three distinct heuristics contribute to the AI's decision-making process:

1. **Heuristic e0:**
   - Basic heuristic calculating the difference in points between the AI and the opponent based on the number of units.
   - Coefficients assign different weights, with the AI unit having the highest coefficient.

2. **Heuristic e1:**
   - Similar to e0 but focuses on the health levels of units rather than the number.
   - Addresses the limitation of e0 by considering units with varying health levels.

3. **Heuristic e2:**
   - Spatial heuristic encouraging units to move strategically across the board.
   - Evaluates the proximity of allies in all four directions for each unit.

These heuristics work synergistically, providing a comprehensive evaluation for decision-making.

## Conclusion

### Possible Improvements

- Refine the influence of the third heuristic to address self-destruct errors.
- Achieve a balanced combination of heuristics for optimal decision-making.
- Implement the minmax algorithm to calculate heuristic scores at each node for better adherence to project requirements.

### What Did We Learn

- Gain insights into AI concepts and strategic decision-making.
- Understand the role of heuristics in evaluating game states.
- Develop teamwork and time management skills in a challenging project.
- Refine debugging skills due to calculations being performed in the background.

Feel free to explore the GitHub repository [here](https://github.com/stunt296/comp472) and contribute to further enhancements. Thank you for engaging in the AI War Game experience!
