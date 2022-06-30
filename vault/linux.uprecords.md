---
id: linux.uprecords
title: Uprecords
desc: ''
updated: 1656591837658
created: 1656591837658
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uprecords

> Displays a summary of historical uptime records.
> More information: <https://manned.org/uprecords>.

- Display a summary of the top 10 historical uptime records:

`uprecords`

- Display the top 25 records:

`uprecords -m {{25}}`

- Display the downtime between reboots instead of the kernel version:

`uprecords -d`

- Show the most recent reboots:

`uprecords -B`

- Don't truncate information:

`uprecords -w`

