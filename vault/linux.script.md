---
id: linux.script
title: Script
desc: ''
updated: 1656591837651
created: 1656591837651
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# script

> Record all terminal output to file.
> More information: <https://manned.org/script>.

- Record a new session to a file named `typescript` in the current directory:

`script`

- Record a new session to a custom filepath:

`script {{path/to/session.out}}`

- Record a new session, appending to an existing file:

`script -a {{path/to/session.out}}`

- Record timing information (data is outputted to the standard error):

`script -t 2> {{path/to/timingfile}}`

