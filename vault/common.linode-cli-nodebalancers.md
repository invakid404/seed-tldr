---
id: common.linode-cli-nodebalancers
title: Linode CLI Nodebalancers
desc: ''
updated: 1694898750775
created: 1694898750775
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# linode-cli nodebalancers

> Manage Linode NodeBalancers.
> See also: `linode-cli`.
> More information: <https://www.linode.com/docs/products/tools/cli/guides/nodebalancers/>.

- List all NodeBalancers:

`linode-cli nodebalancers list`

- Create a new NodeBalancer:

`linode-cli nodebalancers create --region {{region}}`

- View details of a specific NodeBalancer:

`linode-cli nodebalancers view {{nodebalancer_id}}`

- Update an existing NodeBalancer:

`linode-cli nodebalancers update {{nodebalancer_id}} --label {{new_label}}`

- Delete a NodeBalancer:

`linode-cli nodebalancers delete {{nodebalancer_id}}`

- List configurations for a NodeBalancer:

`linode-cli nodebalancers configs list {{nodebalancer_id}}`

- Add a new configuration to a NodeBalancer:

`linode-cli nodebalancers configs create {{nodebalancer_id}} --port {{port}} --protocol {{protocol}}`

