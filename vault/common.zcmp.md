---
id: common.zcmp
title: Zcmp
desc: ''
updated: 1664868765727
created: 1664868765727
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zcmp

> Compare compressed files.
> More information: <https://manned.org/zcmp>.

- Invoke `cmp` on two files compressed via `gzip`:

`zcmp {{path/to/file1.gz}} {{path/to/file2.gz}}`

- Compare a file to its gzipped version (assuming `.gz` exists already):

`zcmp {{path/to/file}}`

