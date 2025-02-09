---
id: common.podman-machine
title: Podman Machine
desc: ''
updated: 1665548851204
created: 1665548851204
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# podman machine

> Create and manage virtual machines running Podman.
> Included with Podman version 4 or greater.
> More information: <https://docs.podman.io/en/latest/markdown/podman-machine.1.html>.

- List existing machines:

`podman machine ls`

- Create a new default machine:

`podman machine init`

- Create a new machine with a specific name:

`podman machine init {{name}}`

- Create a new machine with different resources:

`podman machine init --cpus={{4}} --memory={{4096}} --disk-size={{50}}`

- Start or stop a machine:

`podman machine {{start|stop}} {{name}}`

- Connect to a running machine via SSH:

`podman machine ssh {{name}}`

- Inspect information about a machine:

`podman machine inspect {{name}}`

