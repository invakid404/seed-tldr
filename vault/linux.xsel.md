---
id: linux.xsel
title: Xsel
desc: ''
updated: 1656591837668
created: 1656591837668
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xsel

> X11 selection and clipboard manipulation tool.
> More information: <https://manned.org/xsel>.

- Use a command's output as input of the clip[b]oard (equivalent to `Ctrl + C`):

`echo 123 | xsel -ib`

- Use the contents of a file as input of the clipboard:

`cat {{file}} | xsel -ib`

- Output the clipboard's contents into the terminal (equivalent to `Ctrl + V`):

`xsel -ob`

- Output the clipboard's contents into a file:

`xsel -ob > {{file}}`

- Clear the clipboard:

`xsel -cb`

- Output the X11 primary selection's contents into the terminal (equivalent to a mouse middle-click):

`xsel -op`

