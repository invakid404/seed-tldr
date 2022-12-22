---
id: linux.qm-showcmd
title: Qm Showcmd
desc: ''
updated: 1671712419445
created: 1671712419445
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm showcmd

> Show command line which is used to start the VM (debug info).
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Show command line for a specific virtual machine:

`qm showcmd {{vm_id}}`

- Put each option on a new line to enhance human readability:

`qm showcmd --pretty {{true}} {{vm_id}}`

- Fetch config values from a specific snapshot:

`qm showcmd --snapshot {{string}} {{vm_id}}`

