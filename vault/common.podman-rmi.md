---
id: common.podman-rmi
title: Podman Rmi
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
# podman rmi

> Remove one or more Podman images.
> More information: <https://docs.podman.io/en/latest/markdown/podman-rmi.1.html>.

- Remove one or more images given their names:

`podman rmi {{image:tag}} {{image2:tag}} {{...}}`

- Force remove an image:

`podman rmi --force {{image}}`

- Remove an image without deleting untagged parents:

`podman rmi --no-prune {{image}}`

- Display help:

`podman rmi`

