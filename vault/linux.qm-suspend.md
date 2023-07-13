---
id: linux.qm-suspend
title: Qm Suspend
desc: ''
updated: 1689213025566
created: 1689213025566
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm suspend

> Suspends a virtual machine (VM) in the Proxmox Virtual Environment (PVE).
> Use `--skiplock` and `--skiplockstorage` flags with caution, as they may lead to data corruption in certain situations.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Suspend a virtual machine by id:

`qm suspend {{vm_id}} {{integer}}`

- Skip the lock check when suspending the VM:

`qm suspend {{vm_id}} {{integer}} --skiplock`

- Skip the lock check for storage when suspending the VM:

`qm suspend {{vm_id}} {{integer}} --skiplockstorage`

