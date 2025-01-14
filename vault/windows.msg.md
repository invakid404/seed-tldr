---
id: windows.msg
title: Msg
desc: ''
updated: 1676881477679
created: 1676881477679
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# msg

> Send a message to a specific user or session.
> More information: <https://learn.microsoft.com/windows-server/administration/windows-commands/msg>.

- Send a message to a specified user or session:

`msg {{username|session_name|session_id}} {{message}}`

- Send a message from `stdin`:

`echo "{{message}}" | msg {{username|session_name|session_id}}`

- Send a message to a specific server:

`msg /server:{{server_name}} {{username|session_name|session_id}}`

- Send a message to all users of the current machine:

`msg *`

- Set a delay in seconds for a message:

`msg /time:{{10}}`

