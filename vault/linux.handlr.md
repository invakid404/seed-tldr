---
id: linux.handlr
title: Handlr
desc: ''
updated: 1678572974956
created: 1678572974956
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# handlr

> Manage your default applications.
> More information: <https://github.com/chmln/handlr>.

- Open a URL in the default application:

`handlr open {{https://example.com}}`

- Open a PDF in the default PDF viewer:

`handlr open {{path/to/file.pdf}}`

- Set imv as the default application for PNG files:

`handlr set {{.png}} {{imv.desktop}}`

- Set MPV as the default application for all audio files:

`handlr set {{'audio/*'}} {{mpv.desktop}}`

- List all default apps:

`handlr list`

- Print the default application for PNG files:

`handlr get {{.png}}`

