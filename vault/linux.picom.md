---
id: linux.picom
title: Picom
desc: ''
updated: 1680948954793
created: 1680948954793
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# picom

> Standalone compositor for Xorg.
> More information: <https://wiki.archlinux.org/title/picom>.

- Enable `picom` during a session:

`picom &`

- Start `picom` as a background process:

`picom -b`

- Use a custom configuration file:

`picom --config {{path/to/config_file}}`

