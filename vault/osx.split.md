---
id: osx.split
title: Split
desc: ''
updated: 1677921434472
created: 1677921434472
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
> More information: <https://ss64.com/osx/split.html>.

- Split a file, each split having 10 lines (except the last split):

`split -l {{10}} {{filename}}`

- Split a file by a regular expression. The matching line will be the first line of the next output file:

`split -p {{cat|^[dh]og}} {{filename}}`

- Split a file with 512 bytes in each split (except the last split; use 512k for kilobytes and 512m for megabytes):

`split -b {{512}} {{filename}}`

- Split a file into 5 files. File is split such that each split has same size (except the last split):

`split -n {{5}} {{filename}}`

