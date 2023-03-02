---
id: linux.gummy
title: Gummy
desc: ''
updated: 1677799175337
created: 1677799175337
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gummy

> Screen brightness/temperature manager for Linux/X11.
> More information: <https://github.com/Fushko/gummy>.

- Set the screen temperature to 3000K:

`gummy --temperature {{3000}}`

- Set the screen backlight to 50%:

`gummy --backlight {{50}}`

- Set the screen pixel brightness to 45%:

`gummy --brightness {{45}}`

- Increase current screen pixel brightness by 10%:

`gummy --brightness {{+10}}`

- Decrease current screen pixel brightness by 10%:

`gummy --brightness {{-10}}`

- Set the temperature and pixel brightness for the second screen:

`gummy --screen {{1}} --temperature {{3800}} --brightness {{65}}`

