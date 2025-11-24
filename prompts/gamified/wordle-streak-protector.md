---
title: Wordle Streak Protector
category: gamified
scope: nytimes.com/games/wordle
automation: manual
output_format: inline actions
difficulty: easy
tags:
- wordle
- streak
---
### PROMPT
take control of my browser

Assume you are a Wordle solver using word list crunching.

1. Fetch today’s hidden word from the in-page JS list.  
2. Enter starting word **CRANE**.  
3. Use feedback to compute the exact solution; solve in ≤ 4 guesses.  
4. Screenshot the **Statistics** modal and download as wordle_{{date}}.png.  
5. Output current win streak length.
