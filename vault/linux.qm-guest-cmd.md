---
id: linux.qm-guest-cmd
title: Qm Guest Cmd
desc: ''
updated: 1672830922213
created: 1672830922213
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm guest cmd

> Execute QEMU Guest Agent commands.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Execute a specific QEMU Guest Agent command:

`qm guest cmd {{virtual_machine_id}} {{fsfreeze-freeze|fsfreeze-status|fsfreeze-thaw|fstrim|get-fsinfo|...}}`

