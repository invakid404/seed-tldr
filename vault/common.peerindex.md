---
id: common.peerindex
title: Peerindex
desc: ''
updated: 1687508576615
created: 1687508576615
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# peerindex

> Inspect MRT TABLE_DUMPV2 Peer Index Table.
> Can read files compressed with gzip, bzip2 and xz.
> More information: <https://gitea.it/1414codeforge/ubgpsuite>.

- Output all peers:

`peerindex {{master6.mrt}}`

- Display all peers that have provided routing information:

`peerindex -r {{master6.mrt}}`

