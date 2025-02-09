---
id: common.deemix
title: Deemix
desc: ''
updated: 1686680394348
created: 1686680394348
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# deemix

> A barebone deezer downloader library built from the ashes of Deezloader Remix.
> It can be used as a standalone CLI app or implemented in a UI using the API.
> More information: <https://deemix.app>.

- Download a track or playlist:

`deemix {{https://www.deezer.com/us/track/00000000}}`

- Download track/playlist at a specific bitrate:

`deemix --bitrate {{FLAC|MP3}} {{url}}`

- Download to a specific path:

`deemix --bitrate {{bitrate}} --path {{path}} {{url}}`

- Create a portable deemix config in the current directory:

`deemix --portable --bitrate {{bitrate}} --path {{path}} {{url}}`

