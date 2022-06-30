---
id: linux.nordvpn
title: Nordvpn
desc: ''
updated: 1656591837640
created: 1656591837640
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nordvpn

> Command-line interface for NordVPN.
> More information: <https://nordvpn.com/download/linux/>.

- Interactively log into a NordVPN account:

`nordvpn login`

- Display the connection status:

`nordvpn status`

- Connect to the nearest NordVPN server:

`nordvpn connect`

- List all available countries:

`nordvpn countries`

- Connect to a NordVPN server in a specific country:

`nordvpn connect {{Germany}}`

- Connect to a NordVPN server in a specific country and city:

`nordvpn connect {{Germany}} {{Berlin}}`

- Set autoconnect option:

`nordvpn set autoconnect on`

