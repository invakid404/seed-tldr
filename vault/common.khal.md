---
id: common.khal
title: Khal
desc: ''
updated: 1687904232852
created: 1687904232852
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# khal

> A text-based calendar and scheduling application for the command-line.
> More information: <https://lostpackets.de/khal>.

- Start Khal on interactive mode:

`ikhal`

- Print all events scheduled in personal calendar for the next seven days:

`khal list -a {{personal}} {{today}} {{7d}}`

- Print all events scheduled not in personal calendar for tomorrow at 10:00:

`khal at -d {{personal}} {{tomorrow}} {{10:00}}`

- Print a calendar with a list of events for the next three months:

`khal calendar`

- Add new event to personal calendar:

`khal new -a {{personal}} {{2020-09-08}} {{18:00}} {{18:30}} "{{Dentist appointment}}"`

