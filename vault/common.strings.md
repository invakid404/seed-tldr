---
id: common.strings
title: Strings
desc: ''
updated: 1670145407069
created: 1670145407069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# strings

> Find printable strings in an object file or binary.
> More information: <https://manned.org/strings>.

- Print all strings in a binary:

`strings {{path/to/file}}`

- Limit results to strings at least _length_ characters long:

`strings -n {{length}} {{path/to/file}}`

- Prefix each result with its offset within the file:

`strings -t d {{path/to/file}}`

- Prefix each result with its offset within the file in hexadecimal:

`strings -t x {{path/to/file}}`

