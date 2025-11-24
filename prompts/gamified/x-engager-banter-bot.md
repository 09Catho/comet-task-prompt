---
title: X Engager Banter Bot
category: gamified
scope: twitter.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- twitter
- followers
- meme
---
### PROMPT
take control of my browser

Topics → {{KEYWORD_LIST}}

1. For each topic, search “Latest” tweets.  
2. Pick 5 English tweets < 2 h old by authors < 50 k followers.  
3. Write a ≤ 120-char witty reply, end with one emoji, and attach a GIF via /gif {{TOPIC}}.  
4. Like the parent tweet, wait 90 s, then post the reply.  
5. Stop after 20 replies total or on any rate-limit banner.  
6. List permalinks of all replies.
