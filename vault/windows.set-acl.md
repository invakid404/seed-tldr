---
id: windows.set-acl
title: Set Acl
desc: ''
updated: 1676881477682
created: 1676881477682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Set-Acl

> Changes the security descriptor of a specified item, such as a file or a registry key.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.security/set-acl>.

- Copy a security descriptor from one file to another:

`$OriginAcl = Get-Acl -Path {{path\to\file}}; Set-Acl -Path {{path\to\file}} -AclObject $OriginAcl`

- Use the pipeline operator to pass a descriptor:

`Get-Acl -Path {{path\to\file}} | Set-Acl -Path {{path\to\file}}`

