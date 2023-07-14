---
id: linux.qm-disk-resize
title: Qm Disk Resize
desc: ''
updated: 1689358929717
created: 1689358929717
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm disk resize

> Resize a virtual machine disk in the Proxmox Virtual Environment (PVE).
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Add `n` gigabytes to a virtual disk:

`qm disk resize {{vm_id}} {{disk_name}} +{{n}}G`

