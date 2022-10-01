---
id: common.qm-stop
title: Qm Stop
desc: ''
updated: 1664645376172
created: 1664645376172
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm stop

> Stop a virtual machine.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Stop a virtual machine immediately:

`qm stop {{VM_ID}}`

- Stop a virtual machine and wait for at most 10 seconds:

`qm stop --timeout {{10}} {{VM_ID}}`

- Stop a virtual machine and skip lock (only root can use this option):

`qm stop --skiplock {{true}} {{VM_ID}}`

- Stop a virtual machine and don't deactivate storage volumes:

`qm stop --keepActive {{true}} {{VM_ID}}`

