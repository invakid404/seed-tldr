---
id: common.picom-trans
title: Picom Trans
desc: ''
updated: 1658973683680
created: 1658973683680
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# picom-trans

> Set the window opacity for the `picom` window compositor.
> More information: <https://github.com/yshui/picom>.

- Set the currently focused window opacity to a specific percentage:

`picom-trans --current --opacity {{90}}`

- Set the opacity of a window with a specific name:

`picom-trans --name {{Firefox}} --opacity {{90}}`

- Set the opacity of a specific window selected via mouse cursor:

`picom-trans --select --opacity {{90}}`

- Toggle the opacity of a specific window:

`picom-trans --name {{Firefox}} --toggle`

