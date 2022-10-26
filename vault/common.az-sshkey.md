---
id: common.az-sshkey
title: Az Sshkey
desc: ''
updated: 1666757584500
created: 1666757584500
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az sshkey

> Manage ssh public keys with virtual machines.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/sshkey>.

- Create a new SSH key:

`az sshkey create --name {{name}} --resource-group {{resource_group}}`

- Upload an existing SSH key:

`az sshkey create --name {{name}} --resource-group {{resource_group}} --public-key "{{@path/to/key.pub}}"`

- List all SSH public keys:

`az sshkey list`

- Show information about an SSH public key:

`az sshkey show --name {{name}} --resource-group {{resource_group}}`

