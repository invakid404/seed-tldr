---
id: linux.distrobox-create
title: Distrobox Create
desc: ''
updated: 1679229162639
created: 1679229162639
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-create

> Create a distrobox container. See also: `tldr distrobox`.
> The container created will be tightly integrated with the host, allowing sharing of the user's HOME directory, external storage, external USB devices, graphical apps (X11/Wayland), and audio.
> More information: <https://distrobox.privatedns.org/usage/distrobox-create.html>.

- Create a distrobox container using the Ubuntu image:

`distrobox-create {{container_name}} --image {{ubuntu:latest}}`

- Clone a distrobox container:

`distrobox-create --clone {{container_name}} {{cloned_container_name}}`

