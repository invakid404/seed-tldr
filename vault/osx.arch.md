---
id: osx.arch
title: Arch
desc: ''
updated: 1675797295849
created: 1675797295849
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# arch

> Display the name of the system architecture, or run a command under a different architecture.
> See also `uname`.
> More information: <https://www.unix.com/man-page/osx/1/arch/>.

- Display the system's architecture:

`arch`

- Run a command using x86_64:

`arch -x86_64 "{{command}}"`

- Run a command using arm:

`arch -arm64 "{{command}}"`

