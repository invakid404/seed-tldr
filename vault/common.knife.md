---
id: common.knife
title: Knife
desc: ''
updated: 1689531679633
created: 1689531679633
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# knife

> Interact with a Chef server from a local Chef repo.
> More information: <https://docs.chef.io/knife.html>.

- Bootstrap a new node:

`knife bootstrap {{fqdn_or_ip}}`

- List all registered nodes:

`knife node list`

- Show a node:

`knife node show {{node_name}}`

- Edit a node:

`knife node edit {{node_name}}`

- Edit a role:

`knife role edit {{role_name}}`

- View a data bag:

`knife data bag show {{data_bag_name}} {{data_bag_item}}`

- Upload a local cookbook to the Chef server:

`knife cookbook upload {{cookbook_name}}`

