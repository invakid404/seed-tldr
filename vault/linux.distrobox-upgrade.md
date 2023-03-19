---
id: linux.distrobox-upgrade
title: Distrobox Upgrade
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
# distrobox-upgrade

> Upgrade one or multiple distrobox containers.
> Subcommand of `distrobox`. See also: `tldr distrobox`.
> More information: <https://distrobox.privatedns.org/usage/distrobox-upgrade.html>.

- Upgrade a container using the container's native package manager:

`distrobox-upgrade {{container_name}}`

- Upgrade all containers using the container's native package managers:

`distrobox-upgrade --all`

- Upgrade specific containers via the container's native package manager:

`distrobox-upgrade {{container1 container2 ...}}`

