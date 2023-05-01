---
id: linux.grim
title: Grim
desc: ''
updated: 1682918177872
created: 1682918177872
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# grim

> Grab images (Screenshots) from a Wayland compositor.
> More information: <https://sr.ht/~emersion/grim>.

- Screenshot all outputs:

`grim`

- Screenshot a specific output:

`grim -o {{path/to/output_file}}`

- Screenshot a specific region:

`grim -g "{{<x_position>,<y_position> <width>x<height>}}"`

- Select a specific region and screenshot it, (using slurp):

`grim -g "{{$(slurp)}}"`

- Use a custom filename:

`grim "{{path/to/file.png}}"`

- Screenshot and copy to clipboard:

`grim - | {{clipboard_manager}}`

