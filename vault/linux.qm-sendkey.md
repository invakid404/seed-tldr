---
id: linux.qm-sendkey
title: Qm Sendkey
desc: ''
updated: 1666779932586
created: 1666779932586
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm sendkey

> Send QEMU monitor encoding key event to a virtual machine.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Send the specified key event to a specific virtual machine:

`qm sendkey {{vm_id}} {{key}}`

- Allow root user to send key event and ignore locks:

`qm sendkey --skiplock {{true}} {{vm_id}} {{key}}`

