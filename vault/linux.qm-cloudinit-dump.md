---
id: linux.qm-cloudinit-dump
title: Qm Cloudinit Dump
desc: ''
updated: 1675876629190
created: 1675876629190
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm cloudinit dump

> Generate cloudinit configuration files.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Generate a cloudinit file for a specific configuration type:

`qm cloudinit dump {{virtual_machine_id}} {{meta|network|user}}`

