---
id: common.sfdp
title: Sfdp
desc: ''
updated: 1670142131004
created: 1670142131004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sfdp

> Render an image of a `scaled force-directed` network graph from a `graphviz` file.
> Layouts: `dot`, `neato`, `twopi`, `circo`, `fdp`, `sfdp`, `osage` & `patchwork`.
> More information: <https://graphviz.org/doc/info/command.html>.

- Render a `png` image with a filename based on the input filename and output format (uppercase -O):

`sfdp -T {{png}} -O {{path/to/input.gv}}`

- Render a `svg` image with the specified output filename (lowercase -o):

`sfdp -T {{svg}} -o {{path/to/image.svg}} {{path/to/input.gv}}`

- Render the output in `ps`, `pdf`, `svg`, `fig`, `png`, `gif`, `jpg`, `json`, or `dot` format:

`sfdp -T {{format}} -O {{path/to/input.gv}}`

- Render a `gif` image using `stdin` and `stdout`:

`echo "{{digraph {this -> that} }}" | sfdp -T {{gif}} > {{path/to/image.gif}}`

- Display help:

`sfdp -?`

