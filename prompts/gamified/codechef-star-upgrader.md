---
title: CodeChef Star Upgrader
category: gamified
scope: codechef.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- codechef
- stars
- '{{LANG}}'
---
### PROMPT
take control of my browser

Assume you are a CodeChef specialist coding in {{LANG}}.

1. In the **Practice → Beginner** list, choose the first unsolved problem < 100 submissions.  
2. Paste the pre-tested {{LANG}} solution; click **Submit**.  
3. Wait for verdict—if **AC**, record the rating delta; if not, skip to next problem.  
4. Stop after 5 successful submissions or one WA/TLE.  
5. Summarize stars before → after and problems solved.
