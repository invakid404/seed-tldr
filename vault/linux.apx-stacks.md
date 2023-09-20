---
id: linux.apx-stacks
title: Apx Stacks
desc: ''
updated: 1695183597776
created: 1695183597776
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apx stacks

> Manage stacks in `apx`.
> Note: user-created stack configurations are stored in `~/.local/share/apx/stacks`.
> More information: <https://github.com/Vanilla-OS/apx>.

- Interactively create a new stack configuration:

`apx stacks new`

- Interactively update a stack configuration:

`apx stacks update {{name}}`

- List all available stack configurations:

`apx stacks list`

- Remove a specified stack configuration:

`apx stacks rm --name {{string}}`

- Import a stack configuration:

`apx stacks import --input {{path/to/stack.yml}}`

- Export the stack configuration (Note: the output flag is optional, it is exported to the current working directory by default):

`apx stacks export --name {{string}} --output {{path/to/output_file}}`

