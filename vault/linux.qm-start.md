---
id: linux.qm-start
title: Qm Start
desc: ''
updated: 1664897374215
created: 1664897374215
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm start

> Start a virtual machine on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Start a specific virtual machine:

`qm start {{100}}`

- Specify the QEMU machine type (i.e. the CPU to emulate):

`qm start {{100}} --machine {{q35}}`

- Start a specific virtual machine with a timeout in 60 seconds:

`qm start {{100}} --timeout {{60}}`

