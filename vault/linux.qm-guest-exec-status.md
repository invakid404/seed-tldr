---
id: linux.qm-guest-exec-status
title: Qm Guest Exec Status
desc: ''
updated: 1666459872108
created: 1666459872108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm guest exec-status

> Print the status of the given pid started by the guest-agent on QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Print the status of a specific PID:

`qm guest exec-status {{vm_id}} {{pid}}`

