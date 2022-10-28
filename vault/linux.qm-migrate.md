---
id: linux.qm-migrate
title: Qm Migrate
desc: ''
updated: 1666974652393
created: 1666974652393
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm migrate

> Migrate a virtual machine.
> Used to create a new migration task.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Migrate a specific virtual machine:

`qm migrate {{vm_id}} {{target}}`

- Override the current I/O bandwidth limit with 10 KiB/s:

`qm migrate {{vm_id}} {{target}} --bwlimit 10`

- Allow migration of virtual machines using local devices (root only):

`qm migrate {{vm_id}} {{target}} --force true`

- Use online/live migration if a virtual machine is running:

`qm migrate {{vm_id}} {{target}} --online true`

- Enable live storage migration for local disks:

`qm migrate {{vm_id}} {{target}} --with-local-disks true`

