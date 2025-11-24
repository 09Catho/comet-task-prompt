---
title: Chess.com Tactics Grind
category: gamified
scope: chess.com
automation: manual
output_format: inline actions
difficulty: medium
tags:
- chess.com
- puzzles
---
### PROMPT
take control of my browser

Assume you are an engine-assisted tactician.

1. Start a **Puzzles Rush (3-min)** run.  
2. For each position, read the FEN, compute the best move with Stockfish depth 10, and play it.  
3. End the session when 3 lives are lost or time expires.  
4. Show final score and rating delta.
