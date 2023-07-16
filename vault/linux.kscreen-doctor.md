---
id: linux.kscreen-doctor
title: Kscreen Doctor
desc: ''
updated: 1689531679814
created: 1689531679814
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kscreen-doctor

> Change and manipulate the screen setup.
> More information: <https://invent.kde.org/plasma/libkscreen>.

- Show display output information:

`kscreen-doctor --outputs`

- Set the rotation of a display output with an ID of 1 to the right:

`kscreen-doctor {{output.1.rotation.right}}`

- Set the scale of a display output with an ID of `HDMI-2` to 2 (200%):

`kscreen-doctor {{output.HDMI-2.scale.2}}`

