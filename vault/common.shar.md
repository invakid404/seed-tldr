---
id: common.shar
title: Shar
desc: ''
updated: 1693304222995
created: 1693304222995
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shar

> Create a shell archive.
> More information: <https://manned.org/man/freebsd/shar>.

- Create a shell script that when executed extracts the given files from itself:

`shar {{path/to/file1 path/to/file2 ...}} > {{path/to/archive.sh}}`

