---
id: linux.mpg123
title: Mpg123
desc: ''
updated: 1670142131074
created: 1670142131074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mpg123

> Console MPEG audio player.
> More information: <https://manned.org/mpg123>.

- Play the specified mp3 files:

`mpg123 {{path/to/file1.mp3 path/to/file2.mp3 ...}}`

- Play the mp3 from `stdin`:

`cat {{file.mp3}} | mpg123 -`

- Jump forward to the next song:

`f`

- Jump back to the beginning for the song:

`b`

- Stop or replay the current file:

`s`

- Fast forward:

`.`

- Quit:

`q`

