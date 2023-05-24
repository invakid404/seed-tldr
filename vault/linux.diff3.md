---
id: linux.diff3
title: Diff3
desc: ''
updated: 1684901961504
created: 1684901961504
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diff3

> Compare three files line by line.
> More information: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-diff3.html>.

- Compare files:

`diff3 {{path/to/file1}} {{path/to/file2}} {{path/to/file3}}`

- Show all changes, outlining conflicts:

`diff3 --show-all {{path/to/file1}} {{path/to/file2}} {{path/to/file3}}`

