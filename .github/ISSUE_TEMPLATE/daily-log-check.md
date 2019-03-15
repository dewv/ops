---
name: Daily log check
about: Template for recurring daily log checks.
title: Check server logs
labels: Log check, Daily recurring
assignees: ''

---

Access the production server using the appropriate account. Check the following. If you find anything that needs follow up or investigation, create appropriate Issues in this repository.

- [ ] Check `/var/log/unattended-upgrades/unattended-upgrades.log` to verify that security updates installed without problems.
- [ ] Run `grep 'Accepted password' /var/log/auth.log`; all search hits should be for one of two expected accounts.
- [ ] Check `/var/log/syslog` for anything unusual. (Most entries will be hourly `cron` jobs.)
- [ ] Run `~/logdays.sh 2` to identify log files updated within the last 48 hours. (Replace 2 with 3 on Mondays.) Browse some of these; especially unusual ones; look for anything out of the ordinary.
