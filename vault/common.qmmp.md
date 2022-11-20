---
id: common.qmmp
title: Qmmp
desc: ''
updated: 1668950953587
created: 1668950953587
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qmmp

> An audio player.
> More information: <http://qmmp.ylsoftware.com>.

- Launch qmmp:

`qmmp`

- Start or stop the currently playing audio:

`qmmp --play-pause`

- Seek forwards or backward a specific amount of time in seconds:

`qmmp --seek-{{fwd|bwd}} {{time_in_seconds}}`

- Play the next audio file:

`qmmp --next`

- Play the previous audio file:

`qmmp --previous`

- Print the current volume:

`qmmp --volume-status`

- Increase or decrease the volume of the currently playing audio by 5 steps:

`qmmp --volume-{{inc|dec}}`

