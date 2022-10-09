---
id: linux.qm-reset
title: Qm Reset
desc: ''
updated: 1665289458045
created: 1665289458045
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm reset

> Reset a virtual machine on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Reset a virtual machine:

`qm reset {{vm_id}}`

- Reset a virtual machine and skip lock (only root can use this option):

`qm reset --skiplock {{true}} {{vm_id}}`

