---
id: linux.dconf-reset
title: Dconf Reset
desc: ''
updated: 1664868765741
created: 1664868765741
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dconf reset

> Reset key values in dconf databases.
> See also: `dconf`.
> More information: <https://manned.org/dconf>.

- Reset a specific key value:

`dconf read {{/path/to/key}}`

- Reset a specific directory:

`dconf read -d {{/path/to/directory/}}`

