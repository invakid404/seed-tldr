---
id: linux.scriptreplay
title: Scriptreplay
desc: ''
updated: 1691562059186
created: 1691562059186
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scriptreplay

> Replay a typescript created by the `script` command to `stdout`.
> More information: <https://manned.org/scriptreplay>.

- Replay a typescript at the speed it was recorded:

`scriptreplay {{path/to/timing_file}} {{path/to/typescript}}`

- Replay a typescript at double the original speed:

`scriptreplay {{path/to/timingfile}} {{path/to/typescript}} 2`

- Replay a typescript at half the original speed:

`scriptreplay {{path/to/timingfile}} {{path/to/typescript}} 0.5`

