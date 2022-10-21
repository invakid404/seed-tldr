---
id: linux.loginctl
title: Loginctl
desc: ''
updated: 1666356784535
created: 1666356784535
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# loginctl

> Manage the systemd login manager.
> More information: <https://www.freedesktop.org/software/systemd/man/loginctl.html>.

- Print all current sessions:

`loginctl list-sessions`

- Print all properties of a specific session:

`loginctl show-session {{session_id}} --all`

- Print all properties of a specific user:

`loginctl show-user {{username}}`

- Print a specific property of a user:

`loginctl show-user {{username}} --property={{property_name}}`

- Execute a `loginctl` operation on a remote host:

`loginctl list-users -H {{hostname}}`

