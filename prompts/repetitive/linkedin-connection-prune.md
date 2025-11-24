---
title: LinkedIn Connection Prune
category: repetitive
scope: linkedin.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- linkedin
- cleanup
---
### PROMPT
take control of my browser

Inactivity threshold → {{MONTHS}} months     Daily limit → {{MAX}} removals

1. Open “My Network” → “Connections.”  
2. Filter connections with **no interaction** in ≥ {{MONTHS}} months.  
3. Remove up to {{MAX}} such connections, waiting 5 s between clicks.  
4. Stop if LinkedIn shows any restriction banner.  
5. Report total removed and latest remaining connection count.
