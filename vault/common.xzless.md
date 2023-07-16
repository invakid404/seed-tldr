---
id: common.xzless
title: Xzless
desc: ''
updated: 1689488527910
created: 1689488527910
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xzless

> Display text from `xz` and `lzma` compressed files.
> See also: `less`.
> More information: <https://manned.org/xzless>.

- View a compressed file:

`xzless {{path/to/file}}`

- View a compressed file and display line numbers:

`xzless --LINE-NUMBERS {{path/to/file}}`

- View a compressed file and quit if the entire file can be displayed on the first screen:

`xzless --quit-if-one-screen {{path/to/file}}`

