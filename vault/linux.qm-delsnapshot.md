---
id: linux.qm-delsnapshot
title: Qm Delsnapshot
desc: ''
updated: 1665297161390
created: 1665297161390
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm delsnapshot

> Delete virtual machine snapshots.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Delete a snapshot:

`qm delsnapshot {{vm_id}} {{snapshot_name}}`

- Delete a snapshot from a configuration file (even if removing the disk snapshot fails):

`qm delsnapshot {{vm_id}} {{snapshot_name}} --force 1`

