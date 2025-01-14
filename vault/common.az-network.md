---
id: common.az-network
title: Az Network
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
# az network

> Manage Azure Network resources.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/network>.

- List network resources in a region that are used against a subscription quota:

`az network list-usages`

- List all virtual networks in a subscription:

`az network vnet list`

- Create a virtual network:

`az network vnet create --address-prefixes {{10.0.0.0/16}} --name {{vnet}} --resource_group {{group_name}} --submet-name {{subnet}} --subnet-prefixes {{10.0.0.0/24}}`

- Enable accelerated networking for a network interface card:

`az network nic update --accelerated-networking true --name {{nic}} --resource-group {{resource_group}}`

