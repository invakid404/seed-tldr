---
id: common.play
title: Play
desc: ''
updated: 1689531679689
created: 1689531679689
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# play

> Audio player of SoX - Sound eXchange.
> Plays any audio, with audio formats identified by the extension.
> More information: <http://sox.sourceforge.net>.

- Play the given audio file:

`play {{audiofile}}`

- Play the given audio files:

`play {{audiofile1}} {{audiofile2}}`

- Play the given audio at twice the speed:

`play {{audiofile}} speed 2.0`

- Play the given audio in reverse:

`play {{audiofile}} reverse`

