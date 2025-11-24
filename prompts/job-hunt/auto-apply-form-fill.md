---
title: Auto-Apply Form Fill
category: job-hunt
scope: current tab (ATS form)
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- jobs
- ats
---
### PROMPT
take control of my browser

Assume you are my personal application assistant.

1. Detect whether the page is Greenhouse or Lever.  
2. Fill every mandatory field using resume.json & cover_letter.txt.  
3. Upload both files.  
4. Pause on CAPTCHA or custom questionnaire and announce “Manual step required”.  
5. Log a row (Company | Job ID | Status) to apply_log.csv.  
6. Show a checklist of fields marked Filled ✅ or Manual ❌.
