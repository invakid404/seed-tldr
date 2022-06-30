---
id: linux.tcpkill
title: Tcpkill
desc: ''
updated: 1656591837655
created: 1656591837655
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcpkill

> Kills specified in-progress TCP connections.
> More information: <https://manned.org/tcpkill>.

- Kill in-progress connections at a specified interface, host and port:

`tcpkill -i {{eth1}} host {{192.95.4.27}} and port {{2266}}`

