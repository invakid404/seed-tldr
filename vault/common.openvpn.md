---
id: common.openvpn
title: Openvpn
desc: ''
updated: 1678486627191
created: 1678486627191
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openvpn

> OpenVPN client and daemon binary.
> More information: <https://openvpn.net/>.

- Connect to server using a config file:

`sudo openvpn {{path/to/client.conf}}`

- Try to set up an insecure peer-to-peer tunnel on bob.example.com host:

`sudo openvpn --remote {{alice.example.com}} --dev {{tun1}} --ifconfig {{10.4.0.1}} {{10.4.0.2}}`

- Connect to the awaiting bob.example.com host without encryption:

`sudo openvpn --remote {{bob.example.com}} --dev {{tun1}} --ifconfig {{10.4.0.2}} {{10.4.0.1}}`

- Create a cryptographic key and save it to file:

`openvpn --genkey secret {{path/to/key}}`

- Try to set up a peer-to-peer tunnel on bob.example.com host with a static key:

`sudo openvpn --remote {{alice.example.com}} --dev {{tun1}} --ifconfig {{10.4.0.1}} {{10.4.0.2}} --secret {{path/to/key}}`

- Connect to the awaiting bob.example.com host with the same static key as on bob.example.com:

`sudo openvpn --remote {{bob.example.com}} --dev {{tun1}} --ifconfig {{10.4.0.2}} {{10.4.0.1}} --secret {{path/to/key}}`

