---
id: windows.setx
title: Setx
desc: ''
updated: 1664897374266
created: 1664897374266
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# setx

> Sets persistent environment variables.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/setx>.

- Set an environment variable for the current user:

`setx {{variable}} {{value}}`

- Set an environment variable for the current machine:

`setx {{variable}} {{value}} /M`

- Set an environment variable for a user on a remote machine:

`setx /s {{hostname}} /u {{username}} /p {{password}} {{variable}} {{value}}`

- Set an environment variable from a registry key value:

`setx {{variable}} /k {{registry\key\path}}`

