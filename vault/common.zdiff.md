---
id: common.zdiff
title: Zdiff
desc: ''
updated: 1664808075137
created: 1664808075137
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zdiff

> Invoke `diff` on gzipped files.
> More information: <https://manned.org/zdiff>.

- Compare two files, uncompressing them if necessary:

`zdiff {{path/to/file1.gz}} {{path/to/file2.gz}}`

- Compare a file to a gzipped archive with the same name:

`zdiff {{path/to/file}}`

