---
name: Daily log check
about: Template for recurring daily log checks.
title: Check server logs
labels: Daily recurring, Log check
assignees: ''

---

Access the production server using the appropriate account. 

Run `./daily.sh YYYY-MM-DD` where `YYYY-MM-DD` represents the start point for your check. On Mondays, this should be the date of the preceding Friday; on other days, it should be the preceding day. (This does mean that some log data will be checked twice, but redundant checks are better than gaps.)

The script walks you through the process of checking various server health indicators. If you find problems or anything that seems out of the ordinary, create an Issue in this repo.

Finally, close this Issue with a comment that *either*
- links to the new Issues you created, *or* 
- says "No issues found".
