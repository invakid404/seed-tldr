---
id: windows.whoami
title: Whoami
desc: ''
updated: 1665899330063
created: 1665899330063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# whoami

> Display details about the current user.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/whoami>.

- Display the username of the current user:

`whoami`

- Display the groups that the current user is a member of:

`whoami /groups`

- Display the privileges of the current user:

`whoami /priv`

- Display the user principal name (UPN) of the current user:

`whoami /upn`

- Display the logon ID of the current user:

`whoami /logonid`

- Display all information for the current user:

`whoami /all`

