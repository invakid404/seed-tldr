---
id: linux.protonvpn-cli-connect
title: Protonvpn CLI Connect
desc: ''
updated: 1689531679843
created: 1689531679843
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# protonvpn-cli connect

> Connect to ProtonVPN.
> More information: <https://protonvpn.com/support/linux-vpn-setup/>.

- Connect to ProtonVPN interactively:

`protonvpn-cli connect`

- Connect to ProtonVPN using the fastest server available:

`protonvpn-cli connect --fastest`

- Connect to ProtonVPN using a specific server with a specific protocol:

`protonvpn-cli connect {{server_name}} --protocol {{udp|tcp}}`

- Connect to ProtonVPN using a random server with a specific protocol:

`protonvpn-cli connect --random --protocol {{udp|tcp}}`

- Connect to ProtonVPN using the fastest Tor-supporting server:

`protonvpn-cli connect --tor`

- Display help:

`protonvpn-cli connect --help`

