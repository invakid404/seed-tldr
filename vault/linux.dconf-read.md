---
id: linux.dconf-read
title: Dconf Read
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
# dconf read

> Read key values from dconf databases.
> See also: `dconf`.
> More information: <https://manned.org/dconf>.

- Print a specific key value:

`dconf read {{/path/to/key}}`

- Print a specific key [d]efault value:

`dconf read -d {{/path/to/key}}`

