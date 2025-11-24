---
title: Lichess Puzzle Rating Climber
category: gamified
scope: lichess.org
automation: manual
output_format: inline actions
difficulty: medium
tags:
- lichess
- puzzles
---
### PROMPT
take control of my browser

Assume you use Stockfish depth {{DEPTH}} for perfect moves.

1. Go to lichess.org/training.  
2. For the current puzzle, call Stockfish depth {{DEPTH}} and play its best move.  
3. If rating gain < 10, click **Skip**; otherwise continue solving until the correct solution is accepted.  
4. Repeat for 10 puzzles or until a wrong attempt ends the streak.  
5. Report starting rating → ending rating, puzzles solved, puzzles skipped.
