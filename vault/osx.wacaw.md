---
id: osx.wacaw
title: Wacaw
desc: ''
updated: 1666097653449
created: 1666097653449
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wacaw

> Command-line tool for macOS to capture both still pictures and video from an attached camera.
> More information: <http://webcam-tools.sourceforge.net>.

- Take a picture from webcam:

`wacaw {{filename}}`

- Record a video:

`wacaw --video {{filename}} --duration {{duration_in_seconds}}`

- Take a picture with custom resolution:

`wacaw --width {{width}} --height {{height}} {{filename}}`

- Copy image just taken to clipboard:

`wacaw --to-clipboard`

- List the devices available:

`wacaw --list-devices`

