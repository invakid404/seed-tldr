---
id: common.terminalizer
title: Terminalizer
desc: ''
updated: 1670310991878
created: 1670310991878
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# terminalizer

> Utility program which records the terminal and generate animated GIFs or share a video.
> More information: <https://terminalizer.com>.

- Create the global config directory:

`terminalizer init`

- Record the terminal and create a recording file:

`terminalizer record {{path/to/file}}`

- Play a recorded file on the terminal:

`terminalizer play {{path/to/file}}`

- Render a recording file as an animated GIF image:

`terminalizer render {{path/to/file}}`

- Upload a video to terminalizer.com:

`terminalizer share {{path/to/file}}`

