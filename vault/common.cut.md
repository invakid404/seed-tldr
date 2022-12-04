---
id: common.cut
title: Cut
desc: ''
updated: 1670142130894
created: 1670142130894
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cut

> Cut out fields from `stdin` or files.
> More information: <https://www.gnu.org/software/coreutils/cut>.

- Print a specific character/field range of each line:

`{{command}} | cut --{{characters|fields}}={{1|1,10|1-10|1-|-10}}`

- Print a range of each line with a specific delimiter:

`{{command}} | cut --delimiter="{{,}}" --{{fields}}={{1}}`

- Print a range of each line of the specific file:

`cut --{{characters}}={{1}} {{path/to/file}}`

