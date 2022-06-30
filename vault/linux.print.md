---
id: linux.print
title: Print
desc: ''
updated: 1656591837645
created: 1656591837645
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# print

> An alias to a `run-mailcap`'s action print.
> Originally `run-mailcap` is used to process mime-type/file.
> More information: <https://manned.org/print>.

- Print action can be used to print any file on default run-mailcap tool:

`print {{filename}}`

- With `run-mailcap`:

`run-mailcap --action=print {{filename}}`

