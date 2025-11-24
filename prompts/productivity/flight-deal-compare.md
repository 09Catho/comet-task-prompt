---
title: Flight Deal Compare
category: productivity
scope: google.com/flights
automation: manual
output_format: markdown table
difficulty: medium
tags:
- travel
- deals
---
### PROMPT
take control of my browser

Assume you are a fare-deal analyst.

Route → {{FROM}} → {{TO}}    Dates → {{RANGE}}

1. In the Google Flights tab, record the lowest round-trip price & URL.  
2. Open kayak.com and skyscanner.com in new tabs; capture their lowest comparable fares.  
3. Build a mini table sorted by price (Site | Airline | Stops | Price | Link) and **bold** the cheapest row.  
4. Finish with one-sentence “Best fare” summary.
