---
id: windows.ipconfig
title: Ipconfig
desc: ''
updated: 1689168470234
created: 1689168470234
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipconfig

> Display and manage the network configuration of Windows.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/ipconfig>.

- Show a list of network adapters:

`ipconfig`

- Show a detailed list of network adapters:

`ipconfig /all`

- Renew the IP addresses for a network adapter:

`ipconfig /renew {{adapter}}`

- Free up the IP addresses for a network adapter:

`ipconfig /release {{adapter}}`

- Show the local DNS cache:

`ipconfig /displaydns`

- Remove all data from the local DNS cache:

`ipconfig /flushdns`

