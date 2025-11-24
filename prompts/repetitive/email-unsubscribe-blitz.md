---
title: Email Unsubscribe Blitz
category: repetitive
scope: gmail.com
automation: manual
output_format: inline actions
difficulty: medium
tags:
- email
- cleanup
---
### PROMPT
take control of my browser

Assume you are an inbox-cleaning specialist.

Label to target → {{GMAIL_LABEL}}     Look-back window → {{DAYS}} days

1. In Gmail, open label {{GMAIL_LABEL}} filtered to mail older than {{DAYS}} days.  
2. For every open message:  
   a. If an “Unsubscribe” link exists, click it and confirm.  
   b. Otherwise create a filter to delete future mail from this sender.  
3. Pause 2 s between actions to avoid server throttle.  
4. Stop after 50 processed emails or when no older mail remains.  
5. Report “Processed {{n}} messages → {{u}} unsubscribed, {{f}} filters created.”
