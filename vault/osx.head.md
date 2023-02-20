---
id: osx.head
title: Head
desc: ''
updated: 1676877466505
created: 1676877466505
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# head

> Output the first part of files.
> More information: <https://keith.github.io/xcode-man-pages/head.1.html>.

- Output the first few lines of a file:

`head --lines {{8}} {{path/to/file}}`

- Output the first few bytes of a file:

`head --bytes {{8}} {{path/to/file}}`

- Output everything but the last few lines of a file:

`head --lines -{{8}} {{path/to/file}}`

- Output everything but the last few bytes of a file:

`head --bytes -{{8}} {{path/to/file}}`

