---
id: common.goimports
title: Goimports
desc: ''
updated: 1691562058996
created: 1691562058996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# goimports

> Updates Go import lines, adding missing ones and removing unreferenced ones.
> More information: <https://godoc.org/golang.org/x/tools/cmd/goimports>.

- Display the completed import source file:

`goimports {{path/to/file}}.go`

- Write the result back to the source file instead of `stdout`:

`goimports -w {{path/to/file}}.go`

- Display diffs and write the result back to the source file:

`goimports -w -d {{path/to/file}}.go`

- Set the import prefix string after 3rd-party packages (comma-separated list):

`goimports -local {{path/to/package}} {{path/to/file}}.go`

