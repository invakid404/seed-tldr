---
id: linux.distrobox-export
title: Distrobox Export
desc: ''
updated: 1693073888624
created: 1693073888624
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-export

> Export app/service/binary from container to host OS.
> Subcommand of `distrobox`. See also: `tldr distrobox`.
> More information: <https://distrobox.privatedns.org/usage/distrobox-export.html>.

- Export an app from the container to the host (the desktop entry/icon will show up in your host system's application list):

`distrobox-export --app {{package}} --extra-flags "--foreground"`

- Export a binary from the container to the host:

`distrobox-export --bin {{path/to/binary}} --export-path {{path/to/binary_on_host}}`

- Export a binary from the container to the host (i.e.`$HOME/.local/bin`) :

`distrobox-export --bin {{path/to/binary}} --export-path {{path/to/export}}`

- Export a service from the container to the host (`--sudo` will run the service as root inside the container):

`distrobox-export --service {{package}} --extra-flags "--allow-newer-config" --sudo`

- Unexport/delete an exported application:

`distrobox-export --app {{package}} --delete`

