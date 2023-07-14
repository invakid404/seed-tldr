---
id: common.mtr
title: Mtr
desc: ''
updated: 1689308504765
created: 1689308504765
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mtr

> Matt's Traceroute: combined traceroute and ping tool.
> More information: <https://www.bitwizard.nl/mtr/>.

- Traceroute to a host and continuously ping all intermediary hops:

`mtr {{example.com}}`

- Disable IP address and host name mapping:

`mtr --no-dns {{example.com}}`

- Generate output after pinging each hop 10 times:

`mtr --report-wide {{example.com}}`

- Force IP IPv4 or IPV6:

`mtr -4 {{example.com}}`

- Wait for a given time (in seconds) before sending another packet to the same hop:

`mtr --interval {{10}} {{example.com}}`

- Display the Autonomous System Number (ASN) for each hop:

`mtr --aslookup {{example.com}}`

- Display both IP address and reverse DNS name:

`mtr --show-ips {{example.com}}`

