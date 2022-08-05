---
id: linux.toolbox-rmi
title: Toolbox Rmi
desc: ''
updated: 1659687976652
created: 1659687976652
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# toolbox rmi

> Remove one or more `toolbox` images.
> See also: `toolbox rm`.
> More information: <https://manned.org/toolbox-rmi.1>.

- Remove a `toolbox` image:

`toolbox rmi {{image_name}}`

- Remove all `toolbox` images:

`toolbox rmi --all`

- Force the removal of a `toolbox` image which is currently being used by a container (the container will be removed as well):

`toolbox rmi --force {{image_name}}`

