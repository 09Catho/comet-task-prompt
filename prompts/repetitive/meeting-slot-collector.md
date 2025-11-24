---
title: Meeting Slot Collector
category: repetitive
scope: calendar.google.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- calendar
- scheduling
---
### PROMPT
take control of my browser

Assume you are my scheduling coordinator.

Attendees → {{EMAIL_LIST}}     Slot options → {{SLOT1}}, {{SLOT2}}, {{SLOT3}}

1. In Google Calendar, create a new event titled “Find a Time: {{TOPIC}}”.  
2. Add attendees {{EMAIL_LIST}} and offer the three proposed time slots.  
3. Send the invite with RSVP request.  
4. Twelve hours later, pick the slot with the most “Yes” responses.  
5. Convert the temporary poll into the final meeting and cancel the unused slots.  
6. Confirm chosen time in a summary note.
