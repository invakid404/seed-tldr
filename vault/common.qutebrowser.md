---
id: common.qutebrowser
title: Qutebrowser
desc: ''
updated: 1670142130996
created: 1670142130996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qutebrowser

> A keyboard-driven, vim-like browser based on PyQt5.
> More information: <https://qutebrowser.org/>.

- Open qutebrowser with a specified storage directory:

`qutebrowser --basedir {{path/to/directory}}`

- Open a qutebrowser instance with temporary settings:

`qutebrowser --set {{content.geolocation}} {{true|false}}`

- Restore a named session of a qutebrowser instance:

`qutebrowser --restore {{session_name}}`

- Launch qutebrowser, opening all URLs using the specified method:

`qutebrowser --target {{auto|tab|tab-bg|tab-silent|tab-bg-silent|window|private-window}}`

- Open qutebrowser with a temporary base directory and print logs to `stdout` as JSON:

`qutebrowser --temp-basedir --json-logging`

