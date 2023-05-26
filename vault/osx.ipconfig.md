---
id: osx.ipconfig
title: Ipconfig
desc: ''
updated: 1685068438575
created: 1685068438575
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ipconfig

> View and control IP configuration state.
> More information: <https://ss64.com/osx/ipconfig.html>.

- List all network interfaces:

`ipconfig getiflist`

- Show the IP address of an interface:

`ipconfig getifaddr {{interface_name}}`

