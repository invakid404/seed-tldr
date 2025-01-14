---
id: windows.shutdown
title: Shutdown
desc: ''
updated: 1676881477683
created: 1676881477683
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shutdown

> A tool for shutting down, restarting or logging off a machine.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/shutdown>.

- Shutdown the current machine:

`shutdown /s`

- Shutdown the current machine force-closing all apps:

`shutdown /s /f`

- Restart the current machine immediately:

`shutdown /r /t 0`

- Hibernate the current machine:

`shutdown /h`

- Log off the current machine:

`shutdown /l`

- Specify a timeout in seconds to wait before shutting down:

`shutdown /s /t {{8}}`

- Abort a shutdown sequence whose timeout is yet to expire:

`shutdown /a`

- Shutdown a remote machine:

`shutdown /m {{\\hostname}}`

