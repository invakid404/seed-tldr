---
id: common.az-config
title: Az Config
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
# az config

> Manage Azure CLI configuration.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/config>.

- Print all configurations:

`az config get`

- Print configurations for a specific section:

`az config get {{section_name}}`

- Set a configuration:

`az config set {{configuration_name}}={{value}}`

- Unset a configuration:

`az config unset {{configuration_name}}`

