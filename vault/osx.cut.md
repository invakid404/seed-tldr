---
id: osx.cut
title: Cut
desc: ''
updated: 1656591837671
created: 1656591837671
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cut

> Cut out fields from stdin or files.
> More information: <https://manned.org/man/freebsd-13.0/cut.1>.

- Print a specific character/field range of each line:

`{{command}} | cut -{{c|f}} {{1|1,10|1-10|1-|-10}}`

- Print a range of each line with a specific delimiter:

`{{command}} | cut -d "{{,}}" -{{c}} {{1}}`

- Print a range of each line of a specific file:

`cut -{{c}} {{1}} {{path/to/file}}`

