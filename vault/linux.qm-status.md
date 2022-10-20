---
id: linux.qm-status
title: Qm Status
desc: ''
updated: 1666279789226
created: 1666279789226
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm status

> Show virtual machine status.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Display the status of a specific virtual machine:

`qm status {{vm_id}}`

- Display detailed status of a specific virtual machine:

`qm status --verbose {{true}} {{vm_id}}`

