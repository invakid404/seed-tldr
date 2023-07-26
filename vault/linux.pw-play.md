---
id: linux.pw-play
title: Pw Play
desc: ''
updated: 1690348479734
created: 1690348479734
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pw-play

> Shorthand tool for pw-cat --playback.
> More information: <https://fedoraproject.org/wiki/QA:Testcase_PipeWire_PipeWire_CLI>.

- Play a wav sound file over the default target:

`pw-play {{path/to/file.wav}}`

- Play a wav sound file at a different volume level:

`pw-play --volume={{0.1}} {{path/to/file.wav}}`

