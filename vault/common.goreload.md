---
id: common.goreload
title: Goreload
desc: ''
updated: 1670145406986
created: 1670145406986
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# goreload

> Live reload utility for Go programs.
> More information: <https://github.com/acoshift/goreload>.

- Set the name of the binary file to watch (defaults to `.goreload`):

`goreload -b {{path/to/binary}} {{path/to/file}}.go`

- Set a custom log prefix (defaults to `goreload`):

`goreload --logPrefix {{prefix}} {{path/to/file}}.go`

- Reload whenever any file changes:

`goreload --all`

