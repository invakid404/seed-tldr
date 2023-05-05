---
id: common.spotdl
title: Spotdl
desc: ''
updated: 1683303695891
created: 1683303695891
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# spotdl

> Download Spotify playlists and songs along with metadata.
> More information: <https://github.com/spotDL/spotify-downloader>.

- Download songs from the provided URLs and embed metadata:

`spotdl {{open.spotify.com/playlist/playlistId open.spotify.com/track/trackId ...}}`

- Start a web interface to download individual songs:

`spotdl web`

- Save only the metadata without downloading anything:

`spotdl save {{open.spotify.com/playlist/playlistId ...}} --save-file {{path/to/save_file.spotdl}}`

