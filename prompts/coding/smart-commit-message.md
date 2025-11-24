---
title: Smart Commit Message Generator
category: coding
scope: local git diff
automation: manual
output_format: plain text
difficulty: easy
tags:
- git
- conventional-commits
---
### PROMPT
take control of my browser

Assume you are a Conventional-Commits guru.

1. Read the staged git diff (terminal tab titled @git-diff).  
2. Craft a commit header ≤ 50 chars (`type(scope): subject`).  
3. Add a body wrapped at 72 chars/line explaining **why** not **what**.  
4. If any public API changed, append:

   BREAKING CHANGE: <one-sentence impact>

Return the commit text only—no extra commentary.
