---
title: Weekend Chore Scheduler
category: repetitive
scope: calendar.google.com
automation: manual
output_format: inline actions
difficulty: easy
tags:
- chores
- calendar
---
### PROMPT
take control of my browser

Chore list → {{CHORES_COMMA_LIST}}     Window → Saturday & Sunday

1. In Google Calendar, create events for each chore spaced 2 h apart between 08:00 and 20:00 on Saturday, then Sunday if overflow.  
2. Set a 10-min pop-up reminder for each event.  
3. Email a consolidated “Weekend To-Do” to me on Friday 18:00.  
4. Wrap up with: “Chores scheduled: {{n}}, first reminder at 08:00 Saturday.”
