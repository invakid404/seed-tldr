---
id: common.ffsend
title: Ffsend
desc: ''
updated: 1670145406953
created: 1670145406953
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ffsend

> Easily and securely share files from command-line.
> More information: <https://gitlab.com/timvisee/ffsend>.

- Upload a file:

`ffsend upload {{path/to/file}}`

- Download a file:

`ffsend download {{url}}`

- Upload a file with password:

`ffsend upload {{path/to/file}} -p {{password}}`

- Download a file protected by password:

`ffsend download {{path/to/file}} -p {{password}}`

- Upload a file and allow 4 downloads:

`ffsend upload {{path/to/file}} -d {{4}}`

