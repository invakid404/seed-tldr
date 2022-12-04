---
id: osx.stat
title: Stat
desc: ''
updated: 1670145407193
created: 1670145407193
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stat

> Display file status.
> More information: <https://ss64.com/osx/stat.html>.

- Show file properties such as size, permissions, creation and access dates among others:

`stat {{path/to/file}}`

- Same as above but verbose (more similar to Linux's `stat`):

`stat -x {{path/to/file}}`

- Show only octal file permissions:

`stat -f %Mp%Lp {{path/to/file}}`

- Show owner and group of the file:

`stat -f "%Su %Sg" {{path/to/file}}`

- Show the size of the file in bytes:

`stat -f "%z %N" {{path/to/file}}`

