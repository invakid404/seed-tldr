---
id: android.cmd
title: Cmd
desc: ''
updated: 1672830921982
created: 1672830921982
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmd

> Android service manager.
> More information: <https://cs.android.com/android/platform/superproject/+/master:frameworks/native/cmds/cmd/>.

- [l]ist all running services:

`cmd -l`

- Call a specific service:

`cmd {{service}}`

- Call a service with specific arguments:

`cmd {{service}} {{arg1 arg2 ...}}`

