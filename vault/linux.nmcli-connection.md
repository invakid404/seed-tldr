---
id: linux.nmcli-connection
title: Nmcli Connection
desc: ''
updated: 1690957227194
created: 1690957227194
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli connection

> Manage connections with NetworkManager.
> This subcommand can also be called with `nmcli c`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- List all NetworkManager connections (shows name, UUID, type and device):

`nmcli connection`

- Activate a connection:

`nmcli connection up uuid {{uuid}}`

- Deactivate a connection:

`nmcli connection down uuid {{uuid}}`

- Create an auto-configured dual stack connection:

`nmcli connection add ifname {{interface_name}} type {{ethernet}} ipv4.method {{auto}} ipv6.method {{auto}}`

- Create a static IPv6-only connection:

`nmcli connection add ifname {{interface_name}} type {{ethernet}} ip6 {{2001:db8::2/64}} gw6 {{2001:db8::1}} ipv6.dns {{2001:db8::1}} ipv4.method {{ignore}}`

- Create a static IPv4-only connection:

`nmcli connection add ifname {{interface_name}} type {{ethernet}} ip4 {{10.0.0.7/8}} gw4 {{10.0.0.1}} ipv4.dns {{10.0.0.1}} ipv6.method {{ignore}}`

- Create a VPN connection using OpenVPN from an OVPN file:

`nmcli connection import type {{openvpn}} file {{path/to/vpn_config.ovpn}}`

