---
id: linux.nmcli-agent
title: Nmcli Agent
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
# nmcli agent

> Run `nmcli` as a NetworkManager secret agent or polkit agent.
> This subcommand can also be called with `nmcli a`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Register `nmcli` as a secret agent and listen for secret requests:

`nmcli agent secret`

- Register `nmcli` as a polkit agent and listen for authorization requests:

`nmcli agent polkit`

- Register `nmcli` as a secret agent and a polkit agent:

`nmcli agent all`

