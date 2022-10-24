---
id: windows.date
title: Date
desc: ''
updated: 1666616106471
created: 1666616106471
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# date

> Displays or sets the system date.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/date>.

- Display the current system date and prompt to enter a new date (leave empty to keep unchanged):

`date`

- Display the current system date without prompting for a new date:

`date /t`

- Change the current system date to a specific date:

`date {{month}}-{{day}}-{{year}}`

