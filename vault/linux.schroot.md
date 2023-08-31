---
id: linux.schroot
title: Schroot
desc: ''
updated: 1693491303917
created: 1693491303917
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# schroot

> Run a command or start an interactive shell with a different root directory. More customizable than `chroot`.
> More information: <https://wiki.debian.org/Schroot>.

- List available chroots:

`schroot --list`

- Run a command in a specific chroot:

`schroot --chroot {{chroot}} {{command}}`

- Run a command with options in a specific chroot:

`schroot --chroot {{chroot}} {{command}} -- {{command_options}}`

- Run a command in all available chroots:

`schroot --all {{command}}`

- Start an interactive shell within a specific chroot as a specific user:

`schroot --chroot {{chroot}} --user {{user}}`

- Begin a new session (a unique session ID is returned on `stdout`):

`schroot --begin-session --chroot {{chroot}}`

- Connect to an existing session:

`schroot --run-session --chroot {{session_id}}`

- End an existing session:

`schroot --end-session --chroot {{session_id}}`

