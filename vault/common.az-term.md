---
id: common.az-term
title: Az Term
desc: ''
updated: 1664897373956
created: 1664897373956
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# az term

> Manage marketplace agreement with marketplaceordering.
> Part of `azure-cli`.
> More information: <https://learn.microsoft.com/cli/azure/term>.

- Print marketplace terms:

`az term show --product "{{product_identifier}}" --plan "{{plan_identifier}}" --publisher "{{publisher_identifier}}"`

- Accept marketplace terms:

`az term accept --product "{{product_identifier}}" --plan "{{plan_identifier}}" --publisher "{{publisher_identifier}}"`

