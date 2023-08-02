---
id: linux.nmcli-radio
title: Nmcli Radio
desc: ''
updated: 1690957227195
created: 1690957227195
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nmcli radio

> Show the status of radio switches or enable/disable them using NetworkManager.
> This subcommand can also be called with `nmcli r`.
> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show status of Wi-Fi:

`nmcli radio wifi`

- Turn Wi-Fi on or off:

`nmcli radio wifi {{on|off}}`

- Show status of WWAN:

`nmcli radio wwan`

- Turn WWAN on or off:

`nmcli radio wwan {{on|off}}`

- Show status of both switches:

`nmcli radio all`

- Turn both switches on or off:

`nmcli radio all {{on|off}}`

