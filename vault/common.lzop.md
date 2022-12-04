---
id: common.lzop
title: Lzop
desc: ''
updated: 1670145407010
created: 1670145407010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lzop

> Compress or decompress files with LZO compression.
> More information: <https://www.lzop.org/>.

- Compress a file into a new file with the `.lzo` suffix:

`lzop {{path/to/file}}`

- Decompress a file:

`lzop -d {{path/to/file}}.lzo`

- Compress a file, while specifying the compression level. 0 = Worst, 9 = Best (Default level is 3):

`lzop -{{level}} {{path/to/file}}`

