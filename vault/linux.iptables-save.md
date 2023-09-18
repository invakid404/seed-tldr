---
id: linux.iptables-save
title: Iptables Save
desc: ''
updated: 1695011007299
created: 1695011007299
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iptables-save

> Save the `iptables` IPv4 configuration.
> Use `ip6tables-save` to to the same for IPv6.
> More information: <https://manned.org/iptables-save>.

- Print the `iptables` configuration:

`sudo iptables-save`

- Print the `iptables` configuration of a specific [t]able:

`sudo iptables-save --table {{table}}`

- Save the `iptables` configuration to a [f]ile:

`sudo iptables-save --file {{path/to/file}}`

