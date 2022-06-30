---
id: linux.conntrack
title: Conntrack
desc: ''
updated: 1656591837610
created: 1656591837610
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# conntrack

> Interact with the Netfilter connection tracking system.
> Search, list, inspect, modify, and delete connection flows.
> More information: <https://manned.org/conntrack>.

- List all currently tracked connections:

`conntrack --dump`

- Display a real-time event log of connection changes:

`conntrack --event`

- Display a real-time event log of connection changes and associated timestamps:

`conntrack --event -o timestamp`

- Display a real-time event log of connection changes for a specific IP address:

`conntrack --event --orig-src {{ip_address}}`

- Delete all flows for a specific source IP address:

`conntrack --delete --orig-src {{ip_address}}`

