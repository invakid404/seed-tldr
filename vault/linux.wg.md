---
id: linux.wg
title: Wg
desc: ''
updated: 1690773385515
created: 1690773385515
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wg

> Manage the configuration of WireGuard interfaces.
> More information: <https://www.wireguard.com/quickstart/>.

- Check status of currently active interfaces:

`sudo wg`

- Generate a new private key:

`wg genkey`

- Generate a public key from a private key:

`wg pubkey < {{path/to/private_key}} > {{path/to/public_key}}`

- Generate a public and private key:

`wg genkey | tee {{path/to/private_key}} | wg pubkey > {{path/to/public_key}}`

- Show the current configuration of a wireguard interface:

`sudo wg showconf {{wg0}}`

