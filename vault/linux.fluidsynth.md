---
id: linux.fluidsynth
title: Fluidsynth
desc: ''
updated: 1691439372221
created: 1691439372221
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fluidsynth

> Synthesize audio from MIDI files.
> More information: <https://github.com/FluidSynth/fluidsynth/wiki/UserManual>.

- Play a MIDI file:

`fluidsynth --audio-driver={{pipewire|pulseaudio}} {{path/to/soundfont.sf2}} {{path/to/file.midi}}`

