---
title: Drive Auto-Organizer
category: repetitive
scope: drive.google.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- drive
- organize
---
### PROMPT
take control of my browser

Archive threshold → {{YEARS}} years

1. In Drive “My files,” list items at root.  
2. Move every *.docx/*.pdf older than {{YEARS}} years into “Archive/{{YEAR_FOLDER}}”.  
3. Move any single video > 500 MB into “Big-Videos”.  
4. Generate moves_log.csv summarizing (File, OldPath, NewPath, Size MB).  
5. Confirm: “Files moved: {{n}}, Space reorganized: {{mb}} MB”.
