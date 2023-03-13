---
id: common.babeld
title: Babeld
desc: ''
updated: 1678684633322
created: 1678684633322
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# babeld

> Routing daemon for Babel which uses firewall-style filters.
> More information: <https://www.irif.fr/~jch/software/babel/babeld.html>.

- Start babeld with a specific configuration file:

`babeld -c {{path/to/babeld.conf}}`

- Start babeld with multiple configuration files (read in order):

`babeld -c {{path/to/ports.conf}} -c {{path/to/filters.conf}} -c {{path/to/interfaces.conf}}`

- Start babeld and daemonise afterwards:

`babeld -D`

- Start babeld and pass a configuration command:

`babeld -C {{'redistribute metric 256'}}`

- Start babeld and specify on which interfaces to operate:

`babeld {{eth0}} {{eth1}} {{wlan0}}`

