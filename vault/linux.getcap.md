---
id: linux.getcap
title: Getcap
desc: ''
updated: 1664714687479
created: 1664714687479
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# getcap

> Command to display the name and capabilities of each specified file.
> More information: <https://manned.org/getcap>.

- Get capabilities for the given files:

`getcap {{path/to/file1 path/to/file2 ...}}`

- Displays all searched entries even if no capabilities are set:

`getcap -v {{path/to/file1 path/to/file2 ...}}`

