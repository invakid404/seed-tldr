---
id: common.xzmore
title: Xzmore
desc: ''
updated: 1685546215603
created: 1685546215603
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xzmore

> Display text from `xz` or `lzma` compressed files.
> Almost equivalent to `xzless`, except it respects the `PAGER` environment variable, uses `more` by default and you cannot pass options to the pager.
> More information: <https://manned.org/xzmore>.

- View a compressed file:

`xzmore {{path/to/file}}`

