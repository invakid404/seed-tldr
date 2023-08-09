---
id: linux.nm-online
title: Nm Online
desc: ''
updated: 1691590574996
created: 1691590574996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nm-online

> Ask NetworkManager whether the network is connected.
> More information: <https://networkmanager.dev/docs/api/latest/nm-online.html>.

- Find out whether the network is connected and print the result to `stdout`:

`nm-online`

- Wait `n` seconds for a connection (30 by default):

`nm-online --timeout {{n}}`

