---
id: windows.reg
title: Reg
desc: ''
updated: 1689531679926
created: 1689531679926
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reg

> Manage keys and their values in the Windows registry.
> Some subcommands such as `reg add` have their own usage documentation.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/reg>.

- Execute a registry command:

`reg {{command}}`

- Display general information and list all available commands:

`reg /?`

- Call help on a specific command:

`reg {{command}} /?`

