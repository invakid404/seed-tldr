---
id: linux.conky
title: Conky
desc: ''
updated: 1667596754304
created: 1667596754304
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# conky

> Light-weight system monitor for X.
> More information: <https://github.com/brndnmtthws/conky>.

- Launch with default, built-in config:

`conky`

- Create a new default config:

`conky -C > ~/.conkyrc`

- Launch Conky with a given config file:

`conky -c {{path/to/config}}`

- Start in the background (daemonize):

`conky -d`

- Align Conky on the desktop:

`conky -a {{top|bottom|middle}}_{{left|right|middle}}`

- Pause for 5 seconds at startup before launching:

`conky -p {{5}}`

