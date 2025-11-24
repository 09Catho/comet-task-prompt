---
title: Habitica XP Farmer
category: gamified
scope: habitica.com
automation: manual
output_format: inline actions
difficulty: easy
tags:
- habitica
- xp
---
### PROMPT
take control of my browser

Assume you reward quick wins.

1. Via Habitica API, fetch today’s due Dailies.  
2. Tick every task tagged quick-win.  
3. If gold ≥ 15, buy the cheapest Market item.  
4. Announce: “Completed {{X}} tasks → +{{Y}} XP, +{{Z}} gold (Purchased: {{ITEM}})”.
