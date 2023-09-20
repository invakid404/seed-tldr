---
id: linux.resolvectl
title: Resolvectl
desc: ''
updated: 1695198038566
created: 1695198038566
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# resolvectl

> Resolve domain names, IPv4 and IPv6 addresses, DNS resource records, and services.
> Introspect and reconfigure the DNS resolver.
> More information: <https://www.freedesktop.org/software/systemd/man/resolvectl.html>.

- Show DNS settings:

`resolvectl status`

- Resolve the IPv4 and IPv6 addresses for one or more domains:

`resolvectl query {{domain1 domain2 ...}}`

- Retrieve the domain of a specified IP address:

`resolvectl query {{ip_address}}`

- Flush all local DNS caches:

`resolvectl flush-caches`

- Display DNS statistics (transactions, cache, and DNSSEC verdicts):

`resolvectl statistics`

- Retrieve an MX record of a domain:

`resolvectl --legend={{no}} --type={{MX}} query {{domain}}`

- Resolve an SRV record, for example \_xmpp-server.\_tcp gmail.com:

`resolvectl service _{{service}}._{{protocol}} {{name}}`

- Retrieve a TLS key:

`resolvectl tlsa tcp {{domain}}:443`

