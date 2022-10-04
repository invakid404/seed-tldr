---
id: windows.color
title: Color
desc: ''
updated: 1664897374259
created: 1664897374259
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# color

> Set the console foreground and background colors.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/color>.

- Set the console colors to the default values:

`color`

- List available color values and detailed information:

`color /?`

- Set the console foreground and background to a specific color using hexadecimal numbers (`1-9,a-f`):

`color {{foreground_code}}{{background_code}}`

