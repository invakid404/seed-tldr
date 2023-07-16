---
id: windows.fondue
title: Fondue
desc: ''
updated: 1689531679921
created: 1689531679921
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fondue

> Install optional Windows features.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/fondue>.

- Enable a specific Windows feature:

`fondue /enable-feature:{{feature}}`

- Hide all output messages to the user:

`fondue /enable-feature:{{feature}} /hide-ux:all`

- Specify a caller process name for error reporting:

`fondue /enable-feature:{{feature}} /caller-name:{{name}}`

