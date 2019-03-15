---
name: Services check
about: Template for recurring daily service checks.
title: Check services
labels: Daily recurring, Services check
assignees: ''

---

Access the nagios [Service Availability Report](https://www.dewv.net/nagios/cgi-bin/nagios3/avail.cgi?host=localhost&service=all&timeperiod=last24hours). (On Mondays, adjust the Report period to cover the preceding weekend.)

Verify that all services are 100% OK (green). If not, create an appropriate Issue in this repo.
