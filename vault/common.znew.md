---
id: common.znew
title: Znew
desc: ''
updated: 1664728407389
created: 1664728407389
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# znew

> Recompress files from `.Z` to `.gz` format.
> More information: <https://manned.org/znew>.

- Recompress a file from `.Z` to `.gz` format:

`znew {{path/to/file1.Z}}`

- Recompress multiple files and display the achieved size reduction % per file:

`znew -v {{path/to/file1.Z}} {{path/to/file2.Z}} {{path/to/file3.Z}}`

- Recompress a file using the slowest compression method (for optimal compression):

`znew -9 {{path/to/file1.Z}}`

- Recompress a file, [K]eeping the `.Z` file if it is smaller than the `.gz` file:

`znew -K {{path/to/file1.Z}}`

