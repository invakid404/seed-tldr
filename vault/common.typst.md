---
id: common.typst
title: Typst
desc: ''
updated: 1690204880986
created: 1690204880986
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# typst

> Compile a Typst file to PDF.
> Note: Specifying the output location is optional.
> More information: <https://github.com/typst/typst>.

- List all discoverable fonts in the system and the given directory:

`typst --font-path {{path/to/fonts_directory}} fonts`

- Compile a Typst file:

`typst compile {{path/to/source.typ}} {{path/to/output.pdf}}`

- Watch a Typst file and recompile on changes:

`typst watch {{path/to/source.typ}} {{path/to/output.pdf}}`

