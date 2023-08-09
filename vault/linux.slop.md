---
id: linux.slop
title: Slop
desc: ''
updated: 1691562059188
created: 1691562059188
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# slop

> Get a selection of the screen.
> More information: <https://github.com/naelstrof/slop>.

- Wait for the user to make a selection and output its geometry to `stdout`:

`slop`

- Double click, rather than click and drag, to draw a selection:

`slop -D`

- Highlight the selection rather than outlining it:

`slop -l`

- Specify the output format:

`slop -f {{format_string}}`

- Specify the selection rectangle's color:

`slop -c {{red}},{{green}},{{blue}},{{alpha}}`

