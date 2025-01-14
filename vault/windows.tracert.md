---
id: windows.tracert
title: Tracert
desc: ''
updated: 1681485420511
created: 1681485420511
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tracert

> Receive information about each step in the route between your PC and the target.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/tracert>.

- Trace a route:

`tracert {{IP}}`

- Prevent `tracert` from resolving IP addresses to hostnames:

`tracert /d {{IP}}`

- Force `tracert` to use IPv4 only:

`tracert /4 {{IP}}`

- Force `tracert` to use IPv6 only:

`tracert /6 {{IP}}`

- Specify the maximum number of hops in the search for the target:

`tracert /h {{max_hops}} {{IP}}`

- Display help:

`tracert /?`

