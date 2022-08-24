---
id: common.silicon
title: Silicon
desc: ''
updated: 1661344910165
created: 1661344910165
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# silicon

> Create an image of source code.
> More information: <https://github.com/Aloxaf/silicon>.

- Generate the image from a specific source file:

`silicon  {{path/to/source_file}} --output {{path/to/output_image}}`

- Generate the image from a source file with a specific programing language syntax highlighting (e.g. `rust`, `py`, `js`, etc.):

`silicon  {{path/to/source_file}} --output {{path/to/output_image}} --language {{language|extension}}`

- Generate the image from `stdin`:

`{{command}} | silicon --output {{path/to/output_image}}`

