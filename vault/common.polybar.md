---
id: common.polybar
title: Polybar
desc: ''
updated: 1691000387921
created: 1691000387921
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# polybar

> A fast and easy-to-use status bar.
> More information: <https://github.com/polybar/polybar/wiki>.

- Start Polybar (the bar name is optional if only one bar is defined in the config):

`polybar {{bar_name}}`

- Start Polybar with the specified config:

`polybar --config={{path/to/config.ini}} {{bar_name}}`

- Start Polybar and reload the bar when the config file is modified:

`polybar --reload {{bar_name}}`

