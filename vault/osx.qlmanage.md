---
id: osx.qlmanage
title: Qlmanage
desc: ''
updated: 1684646071602
created: 1684646071602
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# qlmanage

> QuickLook server tool.
> More information: <https://ss64.com/osx/qlmanage.html>.

- Display QuickLook for one or multiple files:

`qlmanage -p {{path/to/file1 path/to/file2 ...}}`

- Compute 300px wide PNG thumbnails of all JPEGs in the current directory and put them in a directory:

`qlmanage {{*.jpg}} -t -s {{300}} {{path/to/directory}}`

- Reset QuickLook:

`qlmanage -r`

