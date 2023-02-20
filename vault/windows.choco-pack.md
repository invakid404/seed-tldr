---
id: windows.choco-pack
title: Choco Pack
desc: ''
updated: 1676881477676
created: 1676881477676
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# choco pack

> Package a NuGet specification into a nupkg file.
> More information: <https://chocolatey.org/docs/commands-pack>.

- Package a NuGet specification to a nupkg file:

`choco pack {{path\to\specification_file}}`

- Package a NuGet specification specifying the version of the resulting file:

`choco pack {{path\to\specification_file}} --version {{version}}`

- Package a NuGet specification to a specific directory:

`choco pack {{path\to\specification_file}} --output-directory {{path\to\output_directory}}`

