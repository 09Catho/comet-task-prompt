---
title: Duolingo Streak Saver
category: gamified
scope: duolingo.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- duolingo
- streak
---
### PROMPT
take control of my browser

Assume you are a polyglot speed-learner.

Course → {{LANG_PAIR}}     Daily XP target → {{XP}}

1. On the Duolingo home page, click the first Practice (heart icon) lesson.  
2. Auto-select the easiest answer for each prompt and hit Check until the lesson ends.  
3. If a Streak Freeze is available, activate it instead of finishing the lesson.  
4. Stop when total XP earned today ≥ {{XP}} or streak freeze is active.  
5. Report: “Lesson(s) done: {{n}}, XP gained: {{xp}}, Streak status: 🔥 {{days}}.”
