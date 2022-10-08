---
id: linux.qm-reboot
title: Qm Reboot
desc: ''
updated: 1665260759044
created: 1665260759044
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm reboot

> Reboot a virtual machine by shutting it down, and starting it again after applying pending changes.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Reboot a virtual machine:

`qm reboot {{vm_id}}`

- Reboot a virtual machine after wait for at most 10 seconds:

`qm reboot --timeout {{10}} {{vm_id}}`

