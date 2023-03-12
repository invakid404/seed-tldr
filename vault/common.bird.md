---
id: common.bird
title: Bird
desc: ''
updated: 1678634222853
created: 1678634222853
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bird

> BIRD Internet Routing Daemon.
> Routing daemon with support for BGP, OSPF, Babel and others.
> More information: <https://bird.network.cz/>.

- Start Bird with a specific configuration file:

`bird -c {{path/to/bird.conf}}`

- Start Bird as a specific user and group:

`bird -u {{username}} -g {{group}}`

