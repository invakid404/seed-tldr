---
id: linux.qm-snapshot
title: Qm Snapshot
desc: ''
updated: 1665559930441
created: 1665559930441
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm snapshot

> Create virtual machine snapshots.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Create a snapshot of a specific virtual machine:

`qm snapshot {{vm_id}} {{snapshot_name}}`

- Create a snapshot with a specific description:

`qm snapshot {{vm_id}} {{snapshot_name}} --description {{description}}`

- Create a snapshot including the vmstate:

`qm snapshot {{vm_id}} {{snapshot_name}} --description {{description}} --vmstate 1`

