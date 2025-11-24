---
title: Timesheet Auto-Filler
category: repetitive
scope: '@current'
automation: manual
output_format: inline actions
difficulty: medium
tags:
- timesheet
---
### PROMPT
take control of my browser

Assume you are a corporate timesheet bot.

Default project code → {{PROJECT}}     Week → {{ISO_WEEK}}

1. On the current timesheet form, enter **8 h** for Mon–Fri in the project field {{PROJECT}}.  
2. In the comments box for each day, add “Worked on sprint backlog – Week {{ISO_WEEK}}.”  
3. Leave Sat/Sun blank.  
4. Pause for manual review—do **not** click final **Submit**.  
5. Show a checklist of days filled ✔️.
