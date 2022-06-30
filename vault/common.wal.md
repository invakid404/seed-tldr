---
id: common.wal
title: Wal
desc: ''
updated: 1656591837593
created: 1656591837593
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wal

> A tool to create color schemes based on the dominant colors of a wallpaper.
> More information: <https://github.com/dylanaraps/pywal>.

- Preview color scheme:

`wal --preview {{image.png}}`

- Create color scheme:

`wal -i {{image.png}}`

- Create a light color scheme:

`wal -i {{image.png}} -l`

- Skip setting the desktop wallpaper:

`wal -i {{image.png}} -n`

- Skip setting the terminal colors:

`wal -i {{image.png}} -s`

- Restore the previously generated color scheme and wallpaper:

`wal -R`

