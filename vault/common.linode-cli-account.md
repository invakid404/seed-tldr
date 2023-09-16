---
id: common.linode-cli-account
title: Linode CLI Account
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
# linode-cli account

> Manage Linode accounts.
> See also: `linode-cli`.
> More information: <https://www.linode.com/docs/products/tools/cli/guides/account/>.

- View account:

`linode-cli account view`

- View account settings:

`linode-cli account settings`

- Make a payment:

`linode-cli account payment-create --cvv {{cvv}} --usd {{amount_in_dollars}}`

- View account notifications:

`linode-cli account notifications-list`

