---
id: linux.virt-viewer
title: Virt Viewer
desc: ''
updated: 1669859502973
created: 1669859502973
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# virt-viewer

> Minimal graphical interface for a virtual machine (VM).
> NOTE: 'domain' refers to the name, UUID or ID for the existing VMs (See: tldr virsh).
> More information: <https://manned.org/virt-viewer>.

- Launch `virt-viewer` with a prompt to select running virtual machines:

`virt-viewer`

- Launch `virt-viewer` for a specific virtual machine by ID, UUID or name:

`virt-viewer "{{domain}}"`

- Wait for a virtual machine to start and automatically reconnect if it shutdown and restarts:

`virt-viewer --reconnect --wait "{{domain}}"`

- Connect to a specific remote virtual machine over TLS:

`virt-viewer --connect "xen//{{url}}" "{{domain}}"`

- Connect to a specific remote virtual machine over SSH:

`virt-viewer --connect "qemu+ssh//{{username}}@{{url}}/system" "{{domain}}"`

