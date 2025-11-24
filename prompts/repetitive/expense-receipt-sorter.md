---
title: Expense Receipt Sorter
category: repetitive
scope: '@current'
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- receipts
- expenses
---
### PROMPT
take control of my browser

Assume you are a finance assistant.

Month → {{YYYY-MM}}

1. Open the Downloads folder in the file-browser tab.  
2. Move every PDF/JPG whose filename contains {{YYYY-MM}} into a new folder “Receipts-{{YYYY-MM}}”.  
3. Rename each file to “{{DATE}}_{{VENDOR}}_₹{{AMOUNT}}.pdf” (info scraped from the receipt text).  
4. Append a CSV line (Date, Vendor, Amount) to receipts_log_{{YYYY-MM}}.csv.  
5. Echo: “Receipts moved: {{n}}, CSV rows added: {{n}}.”
