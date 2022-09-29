---
id: linux.ruget
title: Ruget
desc: ''
updated: 1664431986895
created: 1664431986895
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ruget

> Alternative to wget written in Rust.
> More information: <https://github.com/ksk001100/ruget>.

- Download the contents of a URL to a file:

`ruget {{https://example.com/file}}`

- Download the contents of a URL to a specified [o]utput file:

`ruget --output {{file_name}} {{https://example.com/file}}`

