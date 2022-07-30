---
id: linux.nmcli-networking
title: Nmcli Networking
desc: ''
updated: 1659184494743
created: 1659184494743
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli networking

> Manage the networking status of NetworkManager.
> This subcommand can also be called with `nmcli n`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show the networking status of NetworkManager:

`nmcli networking`

- Enable or disable networking and all interfaces managed by NetworkManager:

`nmcli networking {{on|off}}`

- Show the last known connectivity state:

`nmcli networking connectivity`

- Show the current connectivity state:

`nmcli networking connectivity check`

