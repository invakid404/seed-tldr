---
id: linux.unix2mac
title: Unix2mac
desc: ''
updated: 1684394078589
created: 1684394078589
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unix2mac

> Change Unix-style line endings to macOS-style.
> Replaces LF with CR.
> More information: <https://waterlan.home.xs4all.nl/dos2unix.html>.

- Change the line endings of a file:

`unix2mac {{path/to/file}}`

- Create a copy with macOS-style line endings:

`unix2mac -n {{path/to/unix_file}} {{path/to/mac_file}}`

