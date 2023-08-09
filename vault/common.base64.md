---
id: common.base64
title: Base64
desc: ''
updated: 1691562058924
created: 1691562058924
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# base64

> Encode or decode file or `stdin` to/from Base64, to `stdout`.
> More information: <https://www.gnu.org/software/coreutils/base64>.

- Encode the contents of a file as base64 and write the result to `stdout`:

`base64 {{path/to/file}}`

- Decode the base64 contents of a file and write the result to `stdout`:

`base64 --decode {{path/to/file}}`

- Encode from `stdin`:

`{{somecommand}} | base64`

- Decode from `stdin`:

`{{somecommand}} | base64 --decode`

