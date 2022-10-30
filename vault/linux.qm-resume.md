---
id: linux.qm-resume
title: Qm Resume
desc: ''
updated: 1667128726189
created: 1667128726189
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm resume

> Resume a virtual machine.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Resume a specific virtual machine:

`qm resume {{vm_id}}`

- Resume a specific virtual machine ignoring locks (requires root):

`sudo qm resume {{vm_id}} --skiplock true`

