---
id: linux.bchunk
title: Bchunk
desc: ''
updated: 1687112339010
created: 1687112339010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bchunk

> Convert CD images to a set of `.iso` and `.cdr` tracks.
> More information: <http://he.fi/bchunk>.

- Convert binary CD into a standard iso9960 image file:

`bchunk {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`

- Convert with verbose mode:

`bchunk -v {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`

- Output audio files in WAV format:

`bchunk -w {{path/to/image.bin}} {{path/to/image.cue}} {{path/to/output}}`

