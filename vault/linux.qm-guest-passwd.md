---
id: linux.qm-guest-passwd
title: Qm Guest Passwd
desc: ''
updated: 1666459872108
created: 1666459872108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm guest passwd

> Set the password for a specific user on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Set a password for a specific user in a virtual machine interactively:

`qm guest passwd {{vm_id}} {{username}}`

- Set an already hashed password for a specific user in a virtual machine interactively:

`qm guest passwd {{vm_id}} {{username}} --crypted 1`

