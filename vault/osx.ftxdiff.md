---
id: osx.ftxdiff
title: Ftxdiff
desc: ''
updated: 1671445262375
created: 1671445262375
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ftxdiff

> Compare differences between two fonts.
> More information: <https://developer.apple.com/fonts>.

- Output differences to a specific text file:

`ftxdiff --output {{path/to/fontdiff.txt}} {{path/to/font1.ttc}} {{path/to/font2.ttc}}`

- Include glyph names in output:

`ftxdiff --include-glyph-names`

- Include unicode names in output:

`ftxdiff --include-unicode-names`

