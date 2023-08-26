---
id: windows.choco-new
title: Choco New
desc: ''
updated: 1693073888718
created: 1693073888718
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco new

> Generate new package specification files with Chocolatey.
> More information: <https://chocolatey.org/docs/commands-new>.

- Create a new package skeleton:

`choco new {{package}}`

- Create a new package with a specific version:

`choco new {{package}} --version {{version}}`

- Create a new package with a specific maintainer name:

`choco new {{package}} --maintainer {{maintainer_name}}`

- Create a new package in a custom output directory:

`choco new {{package}} --output-directory {{path/to/directory}}`

- Create a new package with specific 32-bit and 64-bit installer URLs:

`choco new {{package}} url="{{url}}" url64="{{url}}"`

