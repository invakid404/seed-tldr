---
id: linux.envycontrol
title: Envycontrol
desc: ''
updated: 1681907537031
created: 1681907537031
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# envycontrol

> GPU switching utility for Nvidia Optimus laptops.
> More information: <https://github.com/bayasdev/envycontrol>.

- Switch between different GPU modes:

`sudo envycontrol -s {{nvidia|integrated|hybrid}}`

- Specify your display manager manually:

`envycontrol --dm`

- Check current GPU mode:

`sudo envycontrol --query`

- Reset settings:

`sudo envycontrol --reset`

- Display version:

`envycontrol --version`

- Display help:

`envycontrol --help`

