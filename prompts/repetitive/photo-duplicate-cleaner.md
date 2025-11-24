---
title: Photo Duplicate Cleaner
category: repetitive
scope: photos.google.com
automation: manual
output_format: inline actions
difficulty: ⚙️ finicky
tags:
- photos
- duplicates
---
### PROMPT
take control of my browser

Target year folder → {{YEAR}}

1. Go to Google Photos search and filter by year {{YEAR}}.  
2. Compute perceptual hashes; group images with ≥ 95 % similarity.  
3. For each group, keep the highest-resolution photo and move the rest to Trash.  
4. Stop after {{LIMIT}} deletions or when no duplicates remain.  
5. Report groups scanned, duplicates removed, storage freed (MB).
