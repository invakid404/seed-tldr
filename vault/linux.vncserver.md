---
id: linux.vncserver
title: Vncserver
desc: ''
updated: 1656591837660
created: 1656591837660
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vncserver

> Launches a VNC (Virtual Network Computing) desktop.
> More information: <https://manned.org/vncserver.1x>.

- Launch a VNC Server on next available display:

`vncserver`

- Launch a VNC Server with specific screen geometry:

`vncserver --geometry {{width}}x{{height}}`

- Kill an instance of VNC Server running on a specific display:

`vncserver --kill :{{display_number}}`

