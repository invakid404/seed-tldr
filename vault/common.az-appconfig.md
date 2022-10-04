---
id: common.az-appconfig
title: Az Appconfig
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
# az appconfig

> Manage App configurations on Azure.
> Part of `az`, the command-line client for Microsoft Azure.
> More information: <https://learn.microsoft.com/cli/azure/appconfig>.

- Create an App Configuration:

`az appconfig create --name {{name}} --resource-group {{group_name}} --location {{location}}`

- Delete a specific App Configuration:

`az appconfig delete --resource-group {{rg_name}} --name {{appconfig_name}}`

- List all App Configurations under the current subscription:

`az appconfig list`

- List all App Configurations under a specific resource group:

`az appconfig list --resource-group {{rg_name}}`

- Show properties of an App Configuration:

`az appconfig show --name {{appconfig_name}}`

- Update a specific App Configuration:

`az appconfig update --resource-group {{rg_name}} --name {{appconfig_name}}`

