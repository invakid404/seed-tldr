---
id: common.multitail
title: Multitail
desc: ''
updated: 1670145407018
created: 1670145407018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# multitail

> Extension of tail.
> More information: <https://manned.org/multitail>.

- Tail all files matching a pattern in a single stream:

`multitail -Q 1 '{{pattern}}'`

- Tail all files in a directory in a single stream:

`multitail -Q 1 '{{path/to/directory}}/*'`

- Automatically add new files to a window:

`multitail -Q {{pattern}}`

- Show 5 logfiles while merging 2 and put them in 2 columns with only one in the left column:

`multitail -s 2 -sn 1,3 {{mergefile}} -I {{file1}} {{file2}} {{file3}} {{file4}}`

