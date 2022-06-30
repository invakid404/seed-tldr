---
id: linux.dos2unix
title: Dos2unix
desc: ''
updated: 1656620558048
created: 1656620558048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dos2unix

> Change DOS-style line endings to Unix-style.
> Replaces CRLF with LF.
> More information: <https://manned.org/dos2unix>.

- Change the line endings of a file:

`dos2unix {{filename}}`

- Create a copy with Unix-style line endings:

`dos2unix -n {{filename}} {{new_filename}}`

