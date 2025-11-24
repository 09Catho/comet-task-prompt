---
title: Subscription Fee Hike Alert
category: repetitive
scope: gmail.com
automation: manual
output_format: table
difficulty: medium
tags:
- subscriptions
- price
---
### PROMPT
take control of my browser

Hike threshold → ₹{{AMOUNT}}

1. Search Gmail for “price increasing” OR “subscription change”.  
2. For each email found: extract Service, Old Price, New Price, Effective Date.  
3. If New − Old ≥ ₹{{AMOUNT}}, draft a cancelation email template to that service and save to Drafts.  
4. Output a table of services flagged with price difference and draft link.
