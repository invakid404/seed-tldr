---
id: windows.pathping
title: Pathping
desc: ''
updated: 1664897374264
created: 1664897374264
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pathping

> A trace route tool combining features of `ping` and `tracert`.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/pathping>.

- Ping and trace the route to a host:

`pathping {{hostname}}`

- Do not perform reverse lookup of IP address to hostname:

`pathping {{hostname}} -n`

- Specify the maximum number of hops to search for the target (the default is 30):

`pathping {{hostname}} -h {{max_hops}}`

- Specify the milliseconds to wait between pings (the default is 240):

`pathping {{hostname}} -p {{time}}`

- Specify the number of queries per hop (the default is 100):

`pathping {{hostname}} -q {{queries}}`

- Force IPV4 usage:

`pathping {{hostname}} -4`

- Force IPV6 usage:

`pathping {{hostname}} -6`

- Display detailed usage information:

`pathping /?`

