---
id: linux.qmrestore
title: Qmrestore
desc: ''
updated: 1665354274302
created: 1665354274302
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qmrestore

> Restore QemuServer vzdump backups.
> More information: <https://pve.proxmox.com/pve-docs/qmrestore.1.html>.

- Restore virtual machine from given backup file on the original storage:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}}`

- Overwrite existing virtual machine from a given backup file on the original storage:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --force true`

- Restore the virtual machine from a given backup file on specific storage:

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --storage {{local}}`

- Start virtual machine immediately from the backup while restoring in the background (only on Proxmox Backup Server):

`qmrestore {{path/to/vzdump-qemu-100.vma.lzo}} {{100}} --live-restore true`

