---
id: common.dot
title: Dot
desc: ''
updated: 1670142130901
created: 1670142130901
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dot

> Render an image of a `linear directed` network graph from a `graphviz` file.
> Layouts: `dot`, `neato`, `twopi`, `circo`, `fdp`, `sfdp`, `osage` & `patchwork`.
> More information: <https://graphviz.org/doc/info/command.html>.

- Render a `png` image with a filename based on the input filename and output format (uppercase -O):

`dot -T {{png}} -O {{path/to/input.gv}}`

- Render a `svg` image with the specified output filename (lowercase -o):

`dot -T {{svg}} -o {{path/to/image.svg}} {{path/to/input.gv}}`

- Render the output in `ps`, `pdf`, `svg`, `fig`, `png`, `gif`, `jpg`, `json`, or `dot` format:

`dot -T {{format}} -O {{path/to/input.gv}}`

- Render a `gif` image using `stdin` and `stdout`:

`echo "{{digraph {this -> that} }}" | dot -T {{gif}} > {{path/to/image.gif}}`

- Display help:

`dot -?`

