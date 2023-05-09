---
id: linux.avahi-resolve
title: Avahi Resolve
desc: ''
updated: 1683599668675
created: 1683599668675
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# avahi-resolve

> Translate between host names and IP Addresses.
> More information: <https://www.avahi.org/>.

- Resolve a local service to its IPv4:

`avahi-resolve -4 --name {{service.local}}`

- Resolve an IP to a hostname, verbosely:

`avahi-resolve --verbose --address {{IP}}`

