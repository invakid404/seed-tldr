---
id: common.zcat
title: Zcat
desc: ''
updated: 1691562059116
created: 1691562059116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zcat

> Print data from gzip compressed files.
> More information: <https://www.gnu.org/software/gzip/manual/gzip.html>.

- Print the uncompressed contents of a gzipped file to `stdout`:

`zcat {{file.txt.gz}}`

- Print compression details of a gzipped file to `stdout`:

`zcat -l {{file.txt.gz}}`

