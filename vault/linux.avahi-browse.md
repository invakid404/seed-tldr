---
id: linux.avahi-browse
title: Avahi Browse
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
# avahi-browse

> Displays services and hosts exposed on the local network via mDNS/DNS-SD.
> Avahi is compatible with Bonjour (Zeroconf) found in Apple devices.
> More information: <https://www.avahi.org/>.

- List services available on the local network along with their addresses and ports, ignoring ones on the local machine:

`avahi-browse --all --resolve --ignore-local`

- Quickly list services in the local network in SSV format for scripts:

`avahi-browse --all --terminate --parsable`

- List domains in the neighbourhood:

`avahi-browse --browse-domains`

- Limit the search to a particular domain:

`avahi-browse --all --domain={{domain}}`

