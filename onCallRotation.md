# On-call rotation

This document is used to schedule and track staff coverage for unforeseeable operations tasks-- *reactive* work due to system problems or customer requests.

Our Service Level Agreement (SLA) requires continuous support staffing during our customers' business hours: 9:00 am to 5:00 pm, Monday through Friday. IS Managers create a schedule to meet this SLA while accommodating staff scheduling constraints. The current schedule is posted in MS Teams under team DevOps, channel Operations Log.

When your shift starts:
1. post to the Operations Log channel: "Reporting for duty"
2. review Operations Log posts and this repo's Issues created since your last shift so that you are up to speed on recent events

Throughout your shift:
1. monitor the status of our production systems using [Uptime Robot](https://stats.uptimerobot.com/pZrWQtXr5) and the [NLC app status page](https://dewv.net/nlc_attendance/status.json)
2. monitor incoming mail for the Outlook group DevOps (devops@dewv.edu)
3. use your college email to reply to incoming customer mail, using the appropriate message template (see below)
4. examine incoming automated messages that report system events, creating Issues in this repo as appropriate
4. post status updates, questions, etc. to the Operations Log as events warrant

When your shift ends:
1. post to the Operations Log channel: "End of watch"
2. if applicable, summarize your shift: emails sent, Issues created, tasks performed, ongoing problems, etc.

The Operations Log channel contains message templates for email communication with customers. There are templates for these scenarios:
- Notifying customers that we have identified a problem in production
- Responding to a new request/problem report
- Responding to new messages about an existing customer initiated Issue

You are responsible for handling all occurrences of the first two scenarios on your shift. Their message templates require you to insert a "ticket number" that you generate by creating an Issue in this repo. There are corresponding Issue templates to be used for these two scenarios.

You may handle the third scenario *if* it seems urgent or otherwise appropriate. If it does not require immediate attention, you may leave it for the [Customer Service communications process](https://github.com/dewv/professional-experience/blob/master/2.specialist/customerServiceCommunications.md) at our next staff meeting.

