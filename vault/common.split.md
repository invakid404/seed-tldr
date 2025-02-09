---
id: common.split
title: Split
desc: ''
updated: 1670310991871
created: 1670310991871
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# split

> Split a file into pieces.
> More information: <https://www.gnu.org/software/coreutils/split>.

- Split a file, each split having 10 lines (except the last split):

`split -l {{10}} {{path/to/file}}`

- Split a file into 5 files. File is split such that each split has same size (except the last split):

`split -n {{5}} {{path/to/file}}`

- Split a file with 512 bytes in each split (except the last split; use 512k for kilobytes and 512m for megabytes):

`split -b {{512}} {{path/to/file}}`

- Split a file with at most 512 bytes in each split without breaking lines:

`split -C {{512}} {{path/to/file}}`

