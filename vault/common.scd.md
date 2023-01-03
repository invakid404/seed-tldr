---
id: common.scd
title: Scd
desc: ''
updated: 1672719678554
created: 1672719678554
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scd

> File manager focused on shell integration.
> More information: <https://github.com/cshuaimin/scd>.

- Index paths recursively for the very first run:

`scd -ar {{path/to/directory}}`

- Change to a specific directory:

`scd {{path/to/directory}}`

- Change to a path matching specific patterns:

`scd "{{pattern1 pattern2 ...}}"`

- Show selection menu and ranking of 20 most likely directories:

`scd -v`

- Add a specific alias for the current directory:

`scd --alias={{word}}`

- Change to a directory using a specific alias:

`scd {{word}}`

