---
id: common.gnmic-get
title: Gnmic Get
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
# gnmic get

> Get a snapshot of a gnmi network device operation data.
> More information: <https://gnmic.kmrd.dev/cmd/get>.

- Get a snapshot of the device state at a specific path:

`gnmic --address {{ip:port}} get --path {{path}}`

- Query the device state at multiple paths:

`gnmic -a {{ip:port}} get --path {{path1}} --path {{path2}}`

- Query the device state at multiple paths with a common prefix:

`gnmic -a {{ip:port}} get --prefix {{prefix}} --path {{path1}} --path {{path2}}`

- Query the device state and specify reponse encoding (json_ietf):

`gnmic -a {{ip:port}} get --path {{path}} --encoding json_ietf`

