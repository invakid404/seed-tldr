---
id: common.nl
title: Nl
desc: ''
updated: 1691562059041
created: 1691562059041
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nl

> A utility for numbering lines, either from a file, or from `stdin`.
> More information: <https://www.gnu.org/software/coreutils/nl>.

- Number non-blank lines in a file:

`nl {{path/to/file}}`

- Read from `stdout`:

`cat {{path/to/file}} | nl {{options}} -`

- Number only the lines with printable text:

`nl -t {{path/to/file}}`

- Number all lines including blank lines:

`nl -b a {{path/to/file}}`

- Number only the body lines that match a basic regular expression (BRE) pattern:

`nl -b p'FooBar[0-9]' {{path/to/file}}`

