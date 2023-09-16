---
id: common.linode-cli-tickets
title: Linode CLI Tickets
desc: ''
updated: 1694898750776
created: 1694898750776
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# linode-cli tickets

> Manage Linode Support Tickets.
> See also: `linode-cli`.
> More information: <https://www.linode.com/docs/products/tools/cli/guides/account/>.

- List your Support Tickets:

`linode-cli tickets list`

- Open a new Ticket:

`linode-cli tickets create --summary "{{Summary or quick title for the Ticket}}" --description "{{Detailed description of the issue}}"`

- List replies to a Ticket:

`linode-cli tickets replies {{ticket_id}}`

- Reply to a specific Ticket:

`linode-cli tickets reply {{ticket_id}} --description "{{The content of your reply}}"`

