---
id: common.tsort
title: Tsort
desc: ''
updated: 1670145407083
created: 1670145407083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tsort

> Perform a topological sort.
> A common use is to show the dependency order of nodes in a directed acyclic graph.
> More information: <https://www.gnu.org/software/coreutils/tsort>.

- Perform a topological sort consistent with a partial sort per line of input separated by blanks:

`tsort {{path/to/file}}`

