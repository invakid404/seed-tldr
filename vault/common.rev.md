---
id: common.rev
title: Rev
desc: ''
updated: 1670145407055
created: 1670145407055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rev

> Reverse a line of text.
> More information: <https://manned.org/rev>.

- Reverse the text string "hello":

`echo "hello" | rev`

- Reverse an entire file and print to `stdout`:

`rev {{path/to/file}}`

