---
id: common.gnmic
title: Gnmic
desc: ''
updated: 1662059876137
created: 1662059876137
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gnmic

> A gNMI command-line client.
> Manage gNMI network device configuration and view operational data.
> More information: <https://gnmic.kmrd.dev>.

- Request device capabilities:

`gnmic --address {{ip:port}} capabilities`

- Provide a username and password to fetch device capabilities:

`gnmic --address {{ip:port}} --username {{username}} --password {{password}} capabilities`

- Get a snapshot of the device state at a specific path:

`gnmic -a {{ip:port}} get --path {{path}}`

- Update device state at a specific path:

`gnmic -a {{ip:port}} set --update-path {{path}} --update-value {{value}}`

- Subscribe to target state updates under the subtree at a specific path:

`gnmic -a {{ip:port}} subscribe --path {{path}}`

