---
id: common.pixterm
title: Pixterm
desc: ''
updated: 1662039549851
created: 1662039549851
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pixterm

> Image printing in the terminal.
> See also: `chafa`, `catimg`.
> More information: <https://github.com/eliukblau/pixterm>.

- Render a static image directly in the terminal:

`pixterm {{path/to/file}}`

- Use the image's original aspect ratio:

`pixterm -s 2 {{path/to/file}}`

- Specify a custom aspect ratio using a specific number of [t]erminal [r]ows and [c]olumns:

`pixterm -tr {{24}} -tc {{80}} {{path/to/file}}`

- Filter the output with a [m]atte background color and character [d]ithering:

`pixterm -m {{000000}} -d 2 {{path/to/file}}`

