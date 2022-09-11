---
id: common.transmission-daemon
title: Transmission Daemon
desc: ''
updated: 1662917142846
created: 1662917142846
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transmission-daemon

> Daemon controlled with `transmission-remote` or its web interface.
> See also: `transmission`.
> More information: <https://manned.org/transmission-daemon>.

- Start a headless `transmission` session:

`transmission-daemon`

- Start and watch a specific directory for new torrents:

`transmission-daemon --watch-dir {{path/to/directory}}`

- Dump daemon settings in JSON format:

`transmission-daemon --dump-settings > {{path/to/file.json}}`

- Start with specific settings for the web interface:

`transmission-daemon --auth --username {{username}} --password {{password}} --port {{9091}} --allowed {{127.0.0.1}}`

