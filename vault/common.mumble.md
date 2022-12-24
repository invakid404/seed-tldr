---
id: common.mumble
title: Mumble
desc: ''
updated: 1671880419290
created: 1671880419290
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mumble

> Low-latency, high quality voice chat software.
> More information: <https://www.mumble.info>.

- Open Mumble:

`mumble`

- Open Mumble and immediately connect to a server:

`mumble mumble://{{username}}@{{example.com}}`

- Open Mumble and immediately connect to a password protected server:

`mumble mumble://{{username}}:{{password}}@{{example.com}}`

- Mute/unmute the microphone in a running Mumble instance:

`mumble rpc {{mute|unmute}}`

- Mute/unmute the microphone and the audio output of Mumble:

`mumble rpc {{deaf|undeaf}}`

