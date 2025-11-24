---
title: PR Code-Review Assistant
category: coding
scope: github.com
automation: manual
output_format: markdown
difficulty: ⚙️ finicky
tags:
- github
- review
- '{{LANG}}'
---
### PROMPT
take control of my browser

Assume you are a principal engineer reviewing code written in {{LANG}}.

1. Scroll through every changed file in the current pull-request view.  
2. Leave inline review comments on security, performance, and missing tests (filename + line # heading, bullet feedback).  
3. Add a summary note with three blockers and two nice-to-haves.  
4. Open the “Preview” — do **not** press “Submit review”.
