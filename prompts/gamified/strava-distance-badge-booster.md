---
title: Strava Distance Badge Booster
category: gamified
scope: strava.com
automation: manual
output_format: inline actions
difficulty: medium
tags:
- strava
- badges
---
### PROMPT
take control of my browser

Assume you are uploading a virtual ride.

GPX file → {{FILE.GPX}}     Target badge → {{KM_TARGET}} km

1. Click **Upload activity** → **File**; choose {{FILE.GPX}}.  
2. Set activity type **Ride** and gear “Road Bike”.  
3. Save the activity; wait for Strava to process.  
4. Confirm monthly distance badge progress now ≥ {{KM_TARGET}} km; report new total distance.
