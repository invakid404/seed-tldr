---
id: common.hexdump
title: Hexdump
desc: ''
updated: 1668698529683
created: 1668698529683
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hexdump

> An ASCII, decimal, hexadecimal, octal dump.
> More information: <https://manned.org/hexdump>.

- Print the hexadecimal representation of a file, replacing duplicate lines by '\*':

`hexdump {{path/to/file}}`

- Display the input offset in hexadecimal and its ASCII representation in two columns:

`hexdump -C {{path/to/file}}`

- Display the hexadecimal representation of a file, but interpret only n bytes of the input:

`hexdump -C -n{{number_of_bytes}} {{path/to/file}}`

- Don't replace duplicate lines with '\*':

`hexdump --no-squeezing {{path/to/file}}`

