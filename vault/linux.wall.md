---
id: linux.wall
title: Wall
desc: ''
updated: 1676139679911
created: 1676139679911
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wall

> Write a message on the terminals of users currently logged in.
> More information: <https://manned.org/wall>.

- Send a message:

`wall {{message}}`

- Send a message to users that belong to a specific group:

`wall --group {{group_name}} {{message}}`

- Send a message from a file:

`wall {{file}}`

- Send a message with timeout (default 300):

`wall --timeout {{seconds}} {{file}}`

