---
id: common.audacious
title: Audacious
desc: ''
updated: 1670941052244
created: 1670941052244
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# audacious

> An open-source audio player.
> More information: <https://audacious-media-player.org>.

- Launch the program:

`audacious`

- Enqueue a specific directory of audio files:

`audacious --enqueue {{path/to/directory}}`

- Start or stop playback:

`audacious --play-pause`

- Skip forwards or backwards in the playlist:

`audacious --{{fwd|rew}}`

- Stop playback:

`audacious --stop`

- Start a headless version:

`audacious --headless`

- Exit as soon as playback stops or there is nothing to playback:

`audacious --quit-after-play`

