---
id: common.help2man
title: Help2man
desc: ''
updated: 1670142130942
created: 1670142130942
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# help2man

> Produce simple man pages from an executable's `--help` and `--version` output.
> More information: <https://www.gnu.org/software/help2man>.

- Generate a man page for an executable:

`help2man {{executable}}`

- Specify the "name" paragraph in the man page:

`help2man {{executable}} --name {{name}}`

- Specify the section for the man page (defaults to 1):

`help2man {{executable}} --section {{section}}`

- Output to a file instead of `stdout`:

`help2man {{executable}} --output {{path/to/file}}`

- Display detailed help:

`help2man --help`

