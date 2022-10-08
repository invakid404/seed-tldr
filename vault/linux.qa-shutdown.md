---
id: linux.qa-shutdown
title: Qa Shutdown
desc: ''
updated: 1665194404600
created: 1665194404600
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm shutdown

> Shutdown a virtual machine on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Shutdown a virtual machine:

`qm shutdown {{VM_ID}}`

- Shutdown a virtual machine after wait for at most 10 seconds:

`qm shutdown --timeout {{10}} {{VM_ID}}`

- Shutdown a virtual machine and do not deactivate storage volumes:

`qm shutdown --keepActive {{true}} {{VM_ID}}`

- Shutdown a virtual machine and skip lock (only root can use this option):

`qm shutdown --skiplock {{true}} {{VM_ID}}`

- Stop and shutdown a virtual machine:

`qm shutdown --forceStop {{true}} {{VM_ID}}`

