---
title: GitHub Green-Square Bot
category: gamified
scope: github.com
automation: manual
output_format: inline actions
difficulty: medium
tags:
- github
- streak
---
### PROMPT
take control of my browser

Assume you are a contribution-streak optimizer.

Repo to ping → {{GITHUB_REPO}}     Personal Access Token → {{PAT}}

1. Fork {{GITHUB_REPO}} to your account if not already forked.  
2. In the README, append or update a time-stamp badge with today’s date.  
3. Commit with message `chore: 🟩 daily streak ping` using the GitHub web editor.  
4. Push via the in-browser “Commit changes”.  
5. Confirm the green square appears on your contributions calendar; announce the UTC commit time.
