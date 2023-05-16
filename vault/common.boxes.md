---
id: common.boxes
title: Boxes
desc: ''
updated: 1684261200477
created: 1684261200477
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# boxes

> Draw, remove, and repair ASCII art boxes.
> More information: <https://boxes.thomasjensen.com>.

- Draw a box around a string:

`echo "{{string}}" | boxes`

- Remove a box from a string:

`echo "{{string}}" | boxes -r`

- Draw a box with a specific design around a string:

`echo "{{string}}" | boxes -d {{parchment}}`

- Draw a box with a width of 10 and a height of 5:

`echo "{{string}}" | boxes -s {{10}}x{{5}}`

- Draw a box with centered text:

`echo "{{string}}" | boxes -a c`

