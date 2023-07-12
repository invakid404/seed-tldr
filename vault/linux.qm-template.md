---
id: linux.qm-template
title: Qm Template
desc: ''
updated: 1689189290907
created: 1689189290907
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm template

> Create a Proxmox VM template.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Create a template out of a specific virtual machine:

`qm template {{vm_id}}`

