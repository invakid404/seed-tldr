---
id: sunos.prctl
title: Prctl
desc: ''
updated: 1667301578693
created: 1667301578693
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

`prctl {{pid}}`

- Examine process limits and permissions in machine parsable format:

`prctl -P {{pid}}`

- Get specific limit for a running process:

`prctl -n process.max-file-descriptor {{pid}}`

