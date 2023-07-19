---
id: linux.qm-disk-import
title: Qm Disk Import
desc: ''
updated: 1689786885993
created: 1689786885993
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm disk import

> Import a disk image to a virtual machine as an unused disk.
> The supported image formats for `qemu-img`, such as raw, qcow2, qed, vdi, vmdk, and vhd must be used.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Import a VMDK/qcow2/raw disk image using a specific storage name:

`qm importdisk {{vm_id}} {{path/to/disk}} {{storage_name}} --format {{qcow2|raw|vmdk}}`

