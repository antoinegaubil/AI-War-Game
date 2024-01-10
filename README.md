# AI War Game
This Python-based project leverages artificial intelligence techniques, including the implementation of alpha-beta pruning, minimax algorithm, and various heuristics, to create an interactive AI War Game experience, allowing users to input parameters such as tree search depth, maximum time, and maximum round numbers.

### Minimax Algorithm & Alpha-Beta Pruning

Implemented within this project is the minimax algorithm, a pivotal component in adversarial search for two-player games. This algorithm systematically traverses the game tree, assesses terminal states, assigns scores grounded in outcomes, and adeptly backpropagates optimal scores, facilitating strategic decision-making. Furthermore, the integration of alpha-beta pruning enhances efficiency by curtailing superfluous node evaluations, thereby notably decreasing computation time.

### Heuristics


Three heuristics contribute to strategic decision-making in the AI War Game. The first, e0, calculates point differentials based on the number of units, assigning different coefficients for each type of unit. The second, e1, focuses on unit health levels, addressing the limitations of e0. The third, e2, emphasizes a spatial approach, evaluating the proximity of allies in four directions for each unit. Units are encouraged to move strategically, and heuristics work synergistically to gather comprehensive information for decision-making. The goal is a balanced combination of e0, e1, and e2, with e2 influencing decisions in cases of similar heuristic scores without dominating the scoring system.

### User Inputs

1. Game Mode Selection:

Choose between "human vs human," "human vs AI," or "AI vs AI".

2. Alpha-Beta Pruning:

Toggle alpha-beta pruning on or off to influence the efficiency of the algorithm.

3. Maximum Search Time:

Set a time limit for the algorithm's exploration; control computational ressources.

4. Maximum Rounds per Game:

Define the maximum number of rounds in a single game.

5. Depth of Search Tree:

Adjust the depth of the search tree to determine the algorithm's exploration depth.
