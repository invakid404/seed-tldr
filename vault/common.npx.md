---
id: common.npx
title: Npx
desc: ''
updated: 1680959849796
created: 1680959849796
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# npx

> Execute binaries from `npm` packages.
> More information: <https://github.com/npm/npx>.

- Execute the command from a local or remote `npm` package:

`npx {{command}} {{arg1 arg2 ...}}`

- In case multiple commands with the same name exist, it is possible to specify the package name:

`npx --package {{package_name}} {{command}}`

- Run a command if it exists in the current path or in `node_modules/.bin`:

`npx --no-install {{command}} {{command_arguments}}`

- Execute a specific command suppressing any output from `npx` itself:

`npx --quiet {{command}} {{arg1 arg2 ...}}`

- Display help:

`npx --help`

