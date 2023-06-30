---
id: windows.cmdkey
title: Cmdkey
desc: ''
updated: 1688131416014
created: 1688131416014
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmdkey

> Create, show, and delete stored user names and passwords.
> More information: <https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/cmdkey>.

- Show a list of all user credentials:

`cmdkey /list`

- Store credentials for a user that accesses a server:

`cmdkey /add:{{server_name}} /user:{{user_name}}`

- Delete credentials for a specific target:

`cmdkey.exe /delete {{target_name}}`

