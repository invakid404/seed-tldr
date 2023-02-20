---
id: osx.icalbuddy
title: Icalbuddy
desc: ''
updated: 1676877466505
created: 1676877466505
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# icalBuddy

> Command-line utility for printing events and tasks from the macOS calendar database.
> More information: <https://hasseg.org/icalBuddy/>.

- Show events later today:

`icalBuddy --includeOnlyEventsFromNowOn eventsToday`

- Show uncompleted tasks:

`icalBuddy uncompletedTasks`

- Show a formatted list separated by calendar for all events today:

`icalBuddy --formatOutput --separateByCalendar eventsToday`

- Show tasks for a specified number of days:

`icalBuddy --includeOnlyEventsFromNowOn "tasksDueBefore:today+{{8}}"`

- Show events in a time range:

`icalBuddy eventsFrom:{{start_date}} to:{{end_date}}`

