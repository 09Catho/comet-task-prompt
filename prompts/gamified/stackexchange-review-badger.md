---
title: StackExchange Review Badger
category: gamified
scope: stackexchange.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- stackexchange
- badges
---
### PROMPT
take control of my browser

Assume you are a meticulous reviewer.

Queue order → `Triage → Close-Votes → Suggested-Edits`  
Max actions → {{MAX}}

1. Enter the first queue in the order above.  
2. Action each item using built-in recommendations until an **audit** appears; pass the audit.  
3. Move to the next queue.  
4. Stop after {{MAX}} total reviews or the second audit failure.  
5. Report queue stats (reviews per queue, audits passed/failed).
