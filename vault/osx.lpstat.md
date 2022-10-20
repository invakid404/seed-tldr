---
id: osx.lpstat
title: Lpstat
desc: ''
updated: 1666274583025
created: 1666274583025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lpstat

> Display status information about the current classes, jobs, and printers.
> More information: <https://ss64.com/osx/lpstat.html>.

- Show a long listing of printers, classes, and jobs:

`lpstat -l`

- Force encryption when connecting to the CUPS server:

`lpstat -E`

- Show the ranking of print jobs:

`lpstat -R`

- Show whether or not the CUPS server is running:

`lpstat -r`

- Show all status information:

`lpstat -t`

