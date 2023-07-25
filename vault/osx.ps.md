---
id: osx.ps
title: Ps
desc: ''
updated: 1690309172346
created: 1690309172346
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ps

> Information about running processes.
> More information: <https://www.unix.com/man-page/osx/1/ps/>.

- List all running processes:

`ps aux`

- List all running processes including the full command string:

`ps auxww`

- Search for a process that matches a string:

`ps aux | grep {{string}}`

- Get the parent PID of a process:

`ps -o ppid= -p {{pid}}`

- Sort processes by memory usage:

`ps -m`

- Sort processes by CPU usage:

`ps -r`

