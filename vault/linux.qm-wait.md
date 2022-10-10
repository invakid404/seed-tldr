---
id: linux.qm-wait
title: Qm Wait
desc: ''
updated: 1665368716263
created: 1665368716263
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qm wait

> Wait until the virtual machine is stopped.
> More information: <https://pve.proxmox.com/pve-docs/qm.1.html>.

- Wait until the virtual machine is stopped:

`qm wait {{vm_id}}`

- Wait until the virtual machine is stopped with a 10 second timeout:

`qm wait --timeout {{10}} {{vm_id}}`

- Send a shutdown request, then wait until the virtual machine is stopped with a 10 second timeout:

`qm shutdown {{vm_id}} && qm wait --timeout {{10}} {{vm_id}}`

