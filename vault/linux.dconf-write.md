---
id: linux.dconf-write
title: Dconf Write
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
# dconf write

> Write key values in dconf databases.
> See also: `dconf`.
> More information: <https://manned.org/dconf>.

- Write a specific key value:

`dconf write {{/path/to/key}} "{{value}}"`

- Write a specific string key value:

`dconf write {{/path/to/key}} "'{{string}}'"`

- Write a specific integer key value:

`dconf write {{/path/to/key}} "{{5}}"`

- Write a specific boolean key value:

`dconf write {{/path/to/key}} "{{true|false}}"`

- Write a specific array key value:

`dconf write {{/path/to/key}} "[{{'first', 'second', ...}}]"`

- Write a specific empty array key value:

`dconf write {{/path/to/key}} "@as []"`

