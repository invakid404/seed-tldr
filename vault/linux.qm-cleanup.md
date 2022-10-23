---
id: linux.qm-cleanup
title: Qm Cleanup
desc: ''
updated: 1666563913288
created: 1666563913288
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm cleanup

> Clean up resources on QEMU/KVM Virtual Machine Manager like tap devices, VGPUs, etc.
> Called after a VM shuts down, crashes, etc.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Clean up resources:

`qm cleanup {{vm_id}} {{clean-shutdown}} {{guest-requested}}`

