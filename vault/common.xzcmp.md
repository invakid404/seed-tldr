---
id: common.xzcmp
title: Xzcmp
desc: ''
updated: 1689488527910
created: 1689488527910
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xzcmp

> Invokes `cmp` on files compressed with `xz`, `lzma`, `gzip`, `bzip2`, `lzop`, or `zstd`.
> All options specified are passed directly to `cmp`.
> More information: <https://manned.org/xzcmp>.

- Compare two specific files:

`xzcmp {{path/to/file1}} {{path/to/file2}}`

