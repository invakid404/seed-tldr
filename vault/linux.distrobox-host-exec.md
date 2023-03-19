---
id: linux.distrobox-host-exec
title: Distrobox Host Exec
desc: ''
updated: 1679229162643
created: 1679229162643
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-host-exec

> Execute a command on the host from inside a distrobox container.
> Subcommand of `distrobox`. See also: `tldr distrobox`.
> More information: <https://distrobox.privatedns.org/usage/distrobox-host-exec.html>.

- Execute command on the host system from inside the distrobox container:

`distrobox-host-exec "{{command}}"`

- Execute the `ls` command on the host system from inside the container:

`distrobox-host-exec ls`

