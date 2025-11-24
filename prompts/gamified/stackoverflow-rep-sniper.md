---
title: Stack Overflow Rep Sniper
category: gamified
scope: stackoverflow.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- stackoverflow
- rep
---
### PROMPT
take control of my browser

Assume you are a documentation-powered helper.

Tag → {{SO_TAG}}     Max answers → {{N}}

1. Search Stack Overflow for newest **unanswered** questions tagged {{SO_TAG}} sorted by “Newest”.  
2. For each question (up to {{N}}):  
   a. Skim official docs and copy a concise, correct solution.  
   b. Draft an answer (≥ 2 sentences + one code block). **Pause** at the preview—do not submit automatically.  
3. Wait for my final approval to click “Post Your Answer”.  
4. Summarize drafted links in a checklist.
