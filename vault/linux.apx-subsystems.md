---
id: linux.apx-subsystems
title: Apx Subsystems
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
# apx subsystems

> Manage subsystems in `apx`.
> Subsystems are containers that can be created based on pre-existing stacks.
> More information: <https://github.com/Vanilla-OS/apx>.

- Interactively create a new subsystem:

`apx subsystems new`

- List all available subsystems:

`apx subsystems list`

- Reset a specific subsystem to its initial state:

`apx subsystems reset --name {{string}}`

- [f]orce reset a specific subsystem:

`apx subsystems reset --name {{string}} --force`

- Remove a specific subsystem:

`apx subsystems rm --name {{string}}`

- [f]orce remove a specific subsystem:

`apx subsystems rm --name {{string}} --force`

