---
id: linux.iptables-restore
title: Iptables Restore
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
# iptables-restore

> Restore the `iptables` IPv4 configuration.
> Use `ip6tables-restore` to do the same for IPv6.
> More information: <https://manned.org/iptables-restore>.

- Restore the `iptables` configuration from a file:

`sudo iptables-restore {{path/to/file}}`

