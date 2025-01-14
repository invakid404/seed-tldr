---
id: common.ffplay
title: Ffplay
desc: ''
updated: 1688933899757
created: 1688933899757
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ffplay

> A simple and portable media player using the FFmpeg libraries and the SDL library.
> More information: <https://ffmpeg.org/ffplay-all.html>.

- Play a media file:

`ffplay {{path/to/file}}`

- Play audio from a media file without a GUI:

`ffplay -nodisp {{path/to/file}}`

- Play media passed by `ffmpeg` through `stdin`:

`ffmpeg -i {{path/to/file}} -c {{copy}} -f {{media_format}} - | ffplay -`

- Play a video and show motion vectors in real time:

`ffplay -flags2 +export_mvs -vf codecview=mv=pf+bf+bb {{path/to/file}}`

- Show only video keyframes:

`ffplay -vf select="{{eq(pict_type\,PICT_TYPE_I)}}" {{path/to/file}}`

