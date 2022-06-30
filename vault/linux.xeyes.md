---
id: linux.xeyes
title: Xeyes
desc: ''
updated: 1656591837667
created: 1656591837667
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xeyes

> Display eyes on the screen that follow the mouse cursor.
> More information: <https://manned.org/xeyes>.

- Launch xeyes on the local machine's default display:

`xeyes`

- Launch xeyes on a remote machine's display 0, screen 0:

`xeyes -display {{remote_host}}:{{0}}.{{0}}`

