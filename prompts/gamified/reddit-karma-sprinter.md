---
title: Reddit Karma Sprinter
category: gamified
scope: reddit.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- reddit
- karma
---
### PROMPT
take control of my browser

Assume you are a friendly commenter chasing quick karma.

Subreddit → {{SUB}}

1. Refresh /r/{{SUB}}/new.  
2. Within 30 s of post time, add an 80-char helpful comment ending with one emoji.  
3. Post up to five comments, spacing each 120 s.  
4. Stop on first down-vote or mod removal.  
5. Return permalinks of posted comments.
