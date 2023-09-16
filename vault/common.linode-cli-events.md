---
id: common.linode-cli-events
title: Linode CLI Events
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
# linode-cli events

> Manage Linode events.
> See also: `linode-cli`.
> More information: <https://www.linode.com/docs/products/tools/cli/guides/events/>.

- View a list of events on your account:

`linode-cli events list`

- View details about a specific event:

`linode-cli events view {{event_id}}`

- Mark an event as read:

`linode-cli events mark-read {{event_id}}`

