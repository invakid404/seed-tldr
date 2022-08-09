---
id: sunos.prctl
title: Prctl
desc: ''
updated: 1660072904835
created: 1660072904835
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prctl

> Get or set the resource controls of running processes, tasks, and projects.
> More information: <https://www.unix.com/man-page/sunos/1/prctl>.

- Examine process limits and permissions:

`prctl {{PID}}`

- Examine process limits and permissions in machine parsable format:

`prctl -P {{PID}}`

- Get specific limit for a running process:

`prctl -n process.max-file-descriptor {{PID}}`

