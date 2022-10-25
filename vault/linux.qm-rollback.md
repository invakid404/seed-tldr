---
id: linux.qm-rollback
title: Qm Rollback
desc: ''
updated: 1666687203009
created: 1666687203009
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm rollback

> Rollback the VM state to a specified snapshot.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Rollback the state of a specific VM to a specified snapshot:

`qm rollback {{vm_id}} {{snap_name}}`

