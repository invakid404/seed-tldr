---
id: linux.ss
title: Ss
desc: ''
updated: 1672363466457
created: 1672363466457
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ss

> Utility to investigate sockets.
> More information: <https://manned.org/ss.8>.

- Show all TCP/UDP/RAW/UNIX sockets:

`ss -a {{-t|-u|-w|-x}}`

- Filter TCP sockets by states, only/exclude:

`ss {{state/exclude}} {{bucket/big/connected/synchronized/...}}`

- Show all TCP sockets connected to the local HTTPS port (443):

`ss -t src :{{443}}`

- Show all TCP sockets listening on the local 8080 port:

`ss -lt src :{{8080}}`

- Show all TCP sockets along with processes connected to a remote ssh port:

`ss -pt dst :{{ssh}}`

- Show all UDP sockets connected on specific source and destination ports:

`ss -u 'sport == :{{source_port}} and dport == :{{destination_port}}'`

- Show all TCP IPv4 sockets locally connected on the subnet 192.168.0.0/16:

`ss -4t src {{192.168/16}}`

- Kill IPv4 or IPv6 Socket Connection with destination IP 192.168.1.17 and destination port 8080:

`ss --kill dst {{192.168.1.17}} dport = {{8080}}`

