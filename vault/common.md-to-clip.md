---
id: common.md-to-clip
title: Common
desc: ''
updated: 1677674247104
created: 1677674247104
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# md-to-clip

> Converter from tldr-pages to Command Line Interface Pages.
> See also: `clip-view`.
> More information: <https://github.com/command-line-interface-pages/v2-tooling/tree/main/md-to-clip>.

- Convert tldr-pages files and save into the same directories:

`md-to-clip {{path/to/page1.md path/to/page2.md ...}}`

- Convert tldr-pages files and save into a specific directory:

`md-to-clip --output-directory {{path/to/directory}} {{path/to/page1.md path/to/page2.md ...}}`

- Display help:

`md-to-clip --help`

- Display version:

`md-to-clip --version`

