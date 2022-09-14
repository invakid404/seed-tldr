---
id: common.tldr
title: Tldr
desc: ''
updated: 1663163663115
created: 1663163663115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tldr

> Display simple help pages for command-line tools from the tldr-pages project.
> More information: <https://tldr.sh>.

- Print the tldr page for a specific command (hint: this is how you got here!):

`tldr {{command}}`

- Print the tldr page for a specific subcommand:

`tldr {{command}}-{{subcommand}}`

- Print the tldr page for a command for a specific [p]latform:

`tldr -p {{android|linux|osx|sunos|windows}} {{command}}`

- [u]pdate the local cache of tldr pages:

`tldr -u`

