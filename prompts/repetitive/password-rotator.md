---
title: Weekly Password Rotator
category: repetitive
scope: bitwarden.com
automation: manual
output_format: inline actions
difficulty: ⚠️ risk
tags:
- passwords
- security
---
### PROMPT
take control of my browser

Password vault → Bitwarden Web     Rotation list → {{SITES_CSV}}

1. Log in to Bitwarden Web.  
2. For each site in {{SITES_CSV}} (Site, Username, LastReset):  
   a. Open the site’s Change Password page in a new tab.  
   b. Generate a 14-char random pass, copy to clipboard, and paste in both “New” fields.  
   c. Save changes and update the entry in Bitwarden.  
3. If any site blocks automation (CAPTCHA), skip and mark “Manual”.  
4. Export a summary CSV (Site, ResetDate, Status).
