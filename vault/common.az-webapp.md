---
id: common.az-webapp
title: Az Webapp
desc: ''
updated: 1665895276201
created: 1665895276201
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az webapp

> Manage Web Applications hosted in Azure Cloud Services.
> Part of `azure-cli`.
> Mode information: <https://learn.microsoft.com/cli/azure/webapp>.

- List available runtimes for a web application:

`az webapp list-runtimes --os-type {{windows|linux}}`

- Create a web application:

`az webapp up --name {{name}} --location {{location}} --runtime {{runtime}}`

- List all web applications:

`az webapp list`

- Delete a specific web application:

`az webapp delete --name {{name}} --resource-group {{resource_group}}`

