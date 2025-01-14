---
id: common.transmission-create
title: Transmission Create
desc: ''
updated: 1689531679741
created: 1689531679741
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# transmission-create

> Create BitTorrent `.torrent` files.
> More information: <https://manned.org/transmission-create>.

- Create a torrent with 2048 KB as the piece size:

`transmission-create -o {{path/to/example.torrent}} --tracker {{tracker_announce_url}} --piecesize {{2048}} {{path/to/file_or_directory}}`

- Create a private torrent with a 2048 KB piece size:

`transmission-create -p -o {{path/to/example.torrent}} --tracker {{tracker_announce_url}} --piecesize {{2048}} {{path/to/file_or_directory}}`

- Create a torrent with a comment:

`transmission-create -o {{path/to/example.torrent}} --tracker {{tracker_url1}} -c {{comment}} {{path/to/file_or_directory}}`

- Create a torrent with multiple trackers:

`transmission-create -o {{path/to/example.torrent}} --tracker {{tracker_url1}} --tracker {{tracker_url2}} {{path/to/file_or_directory}}`

- Show help page:

`transmission-create --help`

