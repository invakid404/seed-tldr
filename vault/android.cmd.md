---
id: android.cmd
title: Cmd
desc: ''
updated: 1693073888392
created: 1693073888392
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

`cmd {{service}} {{argument1 argument2 ...}}`

