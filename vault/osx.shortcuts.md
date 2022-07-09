---
id: osx.shortcuts
title: Shortcuts
desc: ''
updated: 1656591837676
created: 1656591837676
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shortcuts

> Manage shortcuts from the command-line instead of the `Shortcuts` app.
> More information: <https://support.apple.com/guide/shortcuts-mac/run-shortcuts-from-the-command-line-apd455c82f02/mac>.

- Run the specified shortcut (`Count holidays`):

`shortcuts run "{{Count holidays}}"`

- Print all shortcuts:

`shortcuts list`

- Print all shortcut folders:

`shortcuts list --folders`

- Open the specified shortcut (`Count holidays`) in the Shortcuts editor:

`shortcuts view "{{Count holidays}}"`
