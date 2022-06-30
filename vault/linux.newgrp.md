---
id: linux.newgrp
title: Newgrp
desc: ''
updated: 1656591837639
created: 1656591837639
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# newgrp

> Switch primary group membership.
> More information: <https://manned.org/newgrp>.

- Change user's primary group membership:

`newgrp {{group_name}}`

- Reset primary group membership to user's default group in `/etc/passwd`:

`newgrp`

