---
id: linux.qm
title: Qm
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
# qm

> QEMU/KVM Virtual Machine Manager.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- List all virtual machines:

`qm list`

- Using an ISO file uploaded on the local storage, create a virtual machine with a 4 GB IDE disk on the `local-lvm` storage and an ID of 100:

`qm create {{100}} -ide0 {{local-lvm:4}} -net0 {{e1000}} -cdrom {{local:iso/proxmox-mailgateway_2.1.iso}}`

- Show the configuration of a virtual machine, specifying its ID:

`qm config {{100}}`

- Start a specific virtual machine:

`qm start {{100}}`

- Send a shutdown request, then wait until the virtual machine is stopped:

`qm shutdown {{100}} && qm wait {{100}}`

- Destroy a virtual machine and remove all related resources:

`qm destroy {{100}} --purge`

