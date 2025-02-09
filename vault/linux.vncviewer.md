---
id: linux.vncviewer
title: Vncviewer
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
# vncviewer

> Launches a VNC (Virtual Network Computing) client.
> More information: <https://manned.org/vncviewer>.

- Launch a VNC client which connects to a host on a given display:

`vncviewer {{host}}:{{display_number}}`

- Launch in full-screen mode:

`vncviewer -FullScreen {{host}}:{{display_number}}`

- Launch a VNC client with a specific screen geometry:

`vncviewer --geometry {{width}}x{{height}} {{host}}:{{display_number}}`

- Launch a VNC client which connects to a host on a given port:

`vncviewer {{host}}::{{port}}`

