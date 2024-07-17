# Tetress
 A modified 2 player version of tetris in which 2 agents compete to capture the most space and force their opponent to run out of moves.
![](https://github.com/ReevesyD/Tetress/blob/main/tetress_gif.gif)
## How To Run:
```
python3 -m referee <agent1> <agent2>
```
Example:
```
python3 -m referee smart_agent random_agent
```

There are two agents in this example:
- random_agent : makes moves randomly and has no utility function.
- smart_agent : Utilizes the minimax algorithm with alpha-beta pruning to make optimised and strategic moves.

## Lessons Learned:
I learned a lot about the minimax algorithm, alpha-beta pruning, evaluation functions, heuristics, and strategic thinking. I also had an opportunity to improve my recursive function design, debugging, planning ability, persistence, and most importantly, patience.
