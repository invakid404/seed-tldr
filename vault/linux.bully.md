---
id: linux.bully
title: Bully
desc: ''
updated: 1669864319535
created: 1669864319535
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bully

> Brute-force the WPS pin of a wireless access point.
> Necessary information must be gathered with `airmon-ng` and `airodump-ng` before using `bully`.
> More information: <https://salsa.debian.org/pkg-security-team/bully>.

- Crack the password:

`bully --bssid "{{mac}}" --channel "{{channel}}" --bruteforce "{{interface}}"`

- Display help:

`bully --help`

