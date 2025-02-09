---
id: common.mktorrent
title: Mktorrent
desc: ''
updated: 1689531679654
created: 1689531679654
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mktorrent

> Create BitTorrent metainfo files.
> More information: <https://github.com/Rudde/mktorrent>.

- Create a torrent with 2^21 KB as the piece size:

`mktorrent -a {{tracker_announce_url}} -l {{21}} -o {{path/to/example.torrent}} {{path/to/file_or_directory}}`

- Create a private torrent with a 2^21 KB piece size:

`mktorrent -p -a {{tracker_announce_url}} -l {{21}} -o {{path/to/example.torrent}} {{path/to/file_or_directory}}`

- Create a torrent with a comment:

`mktorrent -c "{{comment}}" -a {{tracker_announce_url}} -l {{21}} -o {{path/to/example.torrent}} {{path/to/file_or_directory}}`

- Create a torrent with multiple trackers:

`mktorrent -a {{tracker_announce_url,tracker_announce_url_2}} -l {{21}} -o {{path/to/example.torrent}} {{path/to/file_or_directory}}`

- Create a torrent with web seed URLs:

`mktorrent -a {{tracker_announce_url}} -w {{web_seed_url}} -l {{21}} -o {{path/to/example.torrent}} {{path/to/file_or_directory}}`

