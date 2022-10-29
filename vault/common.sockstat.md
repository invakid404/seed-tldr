---
id: common.sockstat
title: Sockstat
desc: ''
updated: 1667053279370
created: 1667053279370
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sockstat

> List open Internet or UNIX domain sockets.
> More information: <https://www.freebsd.org/cgi/man.cgi?query=sockstat&sektion=1>.

- View which users/processes are listening to which ports:

`sockstat -l`

