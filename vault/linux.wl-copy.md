---
id: linux.wl-copy
title: Wl Copy
desc: ''
updated: 1656591837661
created: 1656591837661
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wl-copy

> Wayland clipboard manipulation tool.
> See also: `wl-paste`.
> More information: <https://github.com/bugaevc/wl-clipboard>.

- Copy the text to the clipboard:

`wl-copy "{{text}}"`

- Pipe the command (`ls`) output to the clipboard:

`{{ls}} | wl-copy`

- Copy for only one paste and then clear it:

`wl-copy --paste-once "{{text}}"`

- Clear the clipboard:

`wl-copy --clear`

