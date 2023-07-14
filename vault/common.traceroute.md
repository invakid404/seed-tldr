---
id: common.traceroute
title: Traceroute
desc: ''
updated: 1689308504817
created: 1689308504817
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# traceroute

> Print the route packets trace to network host.
> More information: <https://manned.org/traceroute>.

- Traceroute to a host:

`traceroute {{example.com}}`

- Disable IP address and host name mapping:

`traceroute -n {{example.com}}`

- Specify wait time in seconds for response:

`traceroute --wait={{0.5}} {{example.com}}`

- Specify number of queries per hop:

`traceroute --queries={{5}} {{example.com}}`

- Specify size in bytes of probing packet:

`traceroute {{example.com}} {{42}}`

- Determine the MTU to the destination:

`traceroute --mtu {{example.com}}`

- Use ICMP instead of UDP for tracerouting:

`traceroute --icmp {{example.com}}`

