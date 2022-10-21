---
id: linux.qm-config
title: Qm Config
desc: ''
updated: 1666341337241
created: 1666341337241
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm config

> Display the virtual machine configuration with pending configuration changes applied.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Display the virtual machine configuration:

`qm config {{vm_id}}`

- Display the current configuration values instead of pending values for the virtual machine:

`qm config --current {{true}} {{vm_id}}`

- Fetch the configuration values from the given snapshot:

`qm config --snapshot {{snapshot_name}} {{vm_id}}`

