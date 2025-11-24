---
title: Grocery Price Tracker
category: productivity
scope: '@current'
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- grocery
- prices
---
### PROMPT
take control of my browser

Item list → {{ITEMS_JSON}}     Alert drop → {{PERCENT}} %

1. At BigBasket, Amazon Fresh, and JioMart, search each item in {{ITEMS_JSON}}.  
2. Record the current listed price.  
3. Compare to the item’s 30-day average stored in price_history.csv.  
4. If current ≤ avg × (1 − {{PERCENT}}/100), send a WhatsApp alert (API token in env) with price, store link, and ₹ saved.  
5. Append today’s prices to price_history.csv and state items flagged.
