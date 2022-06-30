---
id: common.tailscale-ssh
title: Tailscale Ssh
desc: ''
updated: 1656591837577
created: 1656591837577
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tailscale ssh

> SSH to a Tailscale machine (Linux Only).
> More information: <https://tailscale.com/kb/1193/tailscale-ssh>.

- Advertise/Disable SSH on the host:

`sudo tailscale up --ssh={{true|false}}`

- SSH to a specific host which has Tailscale-SSH enabled:

`tailscale ssh {{username}}@{{host}}`

