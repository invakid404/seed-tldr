---
id: windows.set-service
title: Set Service
desc: ''
updated: 1671599771481
created: 1671599771481
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Set-Service

> Starts, stops, and suspends a service, and changes its properties.
> This command can only be used through PowerShell.
> More information: <https://learn.microsoft.com/powershell/module/microsoft.powershell.management/set-service>.

- Change a display name:

`Set-Service -Name {{hostname}} -DisplayName "{{name}}"`

- Change the startup type of services:

`Set-Service -Name {{service_name}} -StartupType {{Automatic}}`

- Change the description of a service:

`Set-Service -Name {{service_name}} -Description "{{description}}"`

