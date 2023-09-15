---
id: osx.xcodes-runtimes
title: Xcodes Runtimes
desc: ''
updated: 1694769346845
created: 1694769346845
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xcodes runtimes

> Manage Xcode Simulator runtimes.
> More information: <https://github.com/xcodesorg/xcodes>.

- Display all available Simulator runtimes:

`xcodes runtimes --include-betas`

- Download a Simulator runtime:

`xcodes runtimes download {{runtime-name}}`

- Download and install a Simulator runtime:

`xcodes runtimes install {{runtime-name}}`

