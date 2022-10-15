---
id: linux.qm-guest-cmd
title: Qm Guest Cmd
desc: ''
updated: 1665812998444
created: 1665812998444
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm guest cmd

> Execute QEMU Guest Agent commands.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Execute a specific QEMU Guest Agent command:

`qm guest cmd {{vmid}} {{fsfreeze-freeze|fsfreeze-status|fsfreeze-thaw|fstrim|get-fsinfo|get-host-name|get-memory-block-info|get-memory-blocks|get-osinfo|get-time|get-timezone|get-users|get-vcpus|info|network-get-interfaces|ping|shutdown|suspend-disk|suspend-hybrid|suspend-ram}}`

