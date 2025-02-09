---
id: windows.netsh-interface-portproxy
title: Netsh Interface Portproxy
desc: ''
updated: 1689286631797
created: 1689286631797
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# netsh interface portproxy

> Configure and display the status of various network components.
> More information: <https://learn.microsoft.com/en-us/windows-server/networking/technologies/netsh/netsh-interface-portproxy>.

- Display the current port forwarding setup:

`netsh interface portproxy show all`

- Set up IPv4 port forwarding (run in elevated console):

`netsh interface portproxy add v4tov4 listenaddress={{192.168.0.1}} listenport={{8080}}  connectaddress={{10.0.0.1}} connectport={{80}}`

- Remove IPv4 port forwarding (run in elevated console):

`netsh interface portproxy delete v4tov4 listenaddress={{192.168.0.1}} listenport={{8080}}`

- Display help:

`netsh interface portproxy`

