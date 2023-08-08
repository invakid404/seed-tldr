---
id: common.while
title: While
desc: ''
updated: 1691493169340
created: 1691493169340
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# while

> Simple shell loop.
> More information: <https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html#tag_18_09_04_09>.

- Read `stdin` and perform an action on every line:

`while read line; do echo "$line"; done`

- Execute a command forever once every second:

`while :; do {{command}}; sleep 1; done`

