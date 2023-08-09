---
id: linux.flameshot
title: Flameshot
desc: ''
updated: 1691562059144
created: 1691562059144
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# flameshot

> Screenshot utility with a GUI.
> Supports basic image editing, such as text, shapes, colors, and imgur.
> More information: <https://flameshot.org>.

- Create a fullscreen screenshot:

`flameshot full`

- Create a screenshot interactively:

`flameshot gui`

- Create a screenshot and save it to a specific path:

`flameshot gui --path {{path/to/directory}}`

- Create a screenshot interactively in a simplified mode:

`flameshot launcher`

- Create a screenshot from a specific monitor:

`flameshot screen --number {{2}}`

- Create a screenshot and print it to `stdout`:

`flameshot gui --raw`

- Create a screenshot and copy it to the clipboard:

`flameshot gui --clipboard`

- Create a screenshot with a specific delay in milliseconds:

`flameshot full --delay {{5000}}`

