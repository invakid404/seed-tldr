---
id: osx.wacaw
title: Wacaw
desc: ''
updated: 1676877466513
created: 1676877466513
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

`wacaw --video {{filename}} --duration {{10}}`

- Take a picture with custom resolution:

`wacaw --width {{width}} --height {{100}} {{filename}}`

- Copy image just taken to clipboard:

`wacaw --to-clipboard`

- List the devices available:

`wacaw --list-devices`

