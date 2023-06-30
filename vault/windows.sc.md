---
id: windows.sc
title: Sc
desc: ''
updated: 1688131416020
created: 1688131416020
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sc

> Communicate with the Service Control Manager and services.
> More information: <https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/sc-query>.

- Show the status of a service:

`sc queryex {{service_name}}`

- Start a service asynchronously:

`sc start {{service_name}}`

- Stop a service asynchronously:

`sc stop {{service_name}}`

- Set the type of a service:

`sc config {{service_name}} type= {{service_type}}`

