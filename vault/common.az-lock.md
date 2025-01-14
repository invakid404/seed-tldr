---
id: common.az-lock
title: Az Lock
desc: ''
updated: 1664897373955
created: 1664897373955
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az lock

> Manage Azure locks.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/lock>.

- Create a read-only subscription level lock:

`az lock create --name {{lock_name}} --lock-type ReadOnly`

- Create a read-only resource group level lock:

`az lock create --name {{lock_name}} --resource-group {{group_name}} --lock-type ReadOnly`

- Delete a subscription level lock:

`az lock delete --name {{lock_name}}`

- Delete a resource group level lock:

`az lock delete --name {{lock_name}} --resource-group {{group_name}}`

- List out all locks on the subscription level:

`az lock list`

- Show a subscription level lock:

`az lock show -n {{lock_name}}`

