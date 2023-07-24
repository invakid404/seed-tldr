---
id: linux.qm-disk-move
title: Qm Disk Move
desc: ''
updated: 1690233316327
created: 1690233316327
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm disk move

> Move a virtual disk from one storage to another within the same Proxmox cluster.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Move a virtual disk:

`qm disk move {{vm_id}} {{destination}} {{index}}`

- Delete the previous copy of the virtual disk:

`qm disk move -delete {{vm_id}} {{destination}} {{index}}`

