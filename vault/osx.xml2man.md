---
id: osx.xml2man
title: Xml2man
desc: ''
updated: 1656591837679
created: 1656591837679
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xml2man

> Compile MPGL to mdoc.
> More information: <https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/HeaderDoc/mpgl/mpgl.html>.

- Compile an MPGL file to a viewable man page:

`xml2man {{path/to/command.mxml}}`

- Compile an MPGL file to a specific output file:

`xml2man {{path/to/service.mxml}} {{path/to/service.7}}`

- Compile an MPGL file to a specific output file, overwriting if it already exists:

`xml2man -f {{path/to/function.mxml}} {{path/to/function.3}}`

