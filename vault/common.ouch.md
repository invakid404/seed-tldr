---
id: common.ouch
title: Ouch
desc: ''
updated: 1665933997404
created: 1665933997404
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ouch

> Command-line utility for compressing and decompressing files and directories.
> More information: <https://crates.io/crates/ouch>.

- Decompress a specific file:

`ouch decompress {{path/to/archive.tar.xz}}`

- Decompress a file to a specific location:

`ouch decompress {{path/to/archive.tar.xz}} --dir {{path/to/directory}}`

- Decompress multiple files:

`ouch decompress {{path/to/archive1.tar path/to/archive2.tar.gz ...}}`

- Compress files:

`ouch compress {{path/to/file1 path/to/file2 ...}} {{path/to/archive.zip}}`

