---
id: linux.dconf
title: Dconf
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
# dconf

> Manage dconf databases.
> See also: `dconf-read`, `dconf-reset`, `dconf-write`, `gsettings`.
> More information: <https://manned.org/dconf>.

- Print a specific key value:

`dconf read {{/path/to/key}}`

- Print a specific path sub-directories and sub-keys:

`dconf list {{/path/to/directory/}}`

- Write a specific key value:

`dconf write {{/path/to/key}} "{{value}}"`

- Reset a specific key value:

`dconf reset {{/path/to/key}}`

- Watch a specific key/directory for changes:

`dconf watch {{/path/to/key|/path/to/directory/}}`

- Dump a specific directory in INI file format:

`dconf dump {{/path/to/directory/}}`

