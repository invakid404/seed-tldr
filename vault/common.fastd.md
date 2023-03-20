---
id: common.fastd
title: Fastd
desc: ''
updated: 1678684633356
created: 1678684633356
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fastd

> VPN daemon.
> Works on Layer 2 or Layer 3, supports different encryption methods, used by Freifunk.
> More information: <https://fastd.readthedocs.io/en/stable/>.

- Start fastd with a specific configuration file:

`fastd --config {{path/to/fastd.conf}}`

- Start a Layer 3 VPN with an MTU of 1400, loading the rest of the configuration parameters from a file:

`fastd --mode {{tap}} --mtu {{1400}} --config {{path/to/fastd.conf}}`

- Validate a configuration file:

`fastd --verify-config --config {{path/to/fastd.conf}}`

- Generate a new key:

`fastd --generate-key`

- Show the public key to a private key in a configuration file:

`fastd --show-key --config {{path/to/fastd.conf}}`

- Show the current version::

`fastd -v`
