---
id: windows.get-acl
title: Get Acl
desc: ''
updated: 1676881477678
created: 1676881477678
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Get-Acl

> Gets the security descriptor for a resource, such as a file or registry key.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.security/get-acl>.

- Display the ACL for a specific directory:

`Get-Acl {{path\to\directory}}`

- Get an ACL for a registry key:

`Get-Acl -Path {{HKLM:\System\CurrentControlSet\Control}} | Format-List`

