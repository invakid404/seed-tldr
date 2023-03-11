---
id: common.podman-image
title: Podman Image
desc: ''
updated: 1678569286111
created: 1678569286111
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# podman image

> Manage Docker images.
> See also `podman build`, `podman import`, and `podman pull`.
> More information: <https://docs.podman.io/en/latest/markdown/podman-image.1.html>.

- List local Docker images:

`podman image ls`

- Delete unused local Docker images:

`podman image prune`

- Delete all unused images (not just those without a tag):

`podman image prune --all`

- Show the history of a local Docker image:

`podman image history {{image}}`

