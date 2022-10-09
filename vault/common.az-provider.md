---
id: common.az-provider
title: Az Provider
desc: ''
updated: 1665289457729
created: 1665289457729
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az provider

> Manage resource providers.
> Part of `azure-cli`.
> More information: <https://docs.microsoft.com/cli/azure/provider>.

- Register a provider:

`az provider register --namespace {{Microsoft.PolicyInsights}}`

- Unregister a provider:

`az provider unregister --namespace {{Microsoft.Automation}}`

- List all providers for a subscription:

`az provider list`

- Show information about a specific provider:

`az provider show --namespace {{Microsoft.Storage}}`

- List all resource types for a specific provider:

`az provider list --query "[?namespace=='{{Microsoft.Network}}'].resourceTypes[].resourceType"`

