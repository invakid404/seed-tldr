---
id: linux.toolbox-rm
title: Toolbox Rm
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
# toolbox rm

> Remove one or more `toolbox` containers.
> See also: `toolbox rmi`.
> More information: <https://manned.org/toolbox-rm.1>.

- Remove a toolbox container:

`toolbox rm {{container_name}}`

- Remove all `toolbox` containers:

`toolbox rm --all`

- Force the removal of a currently active `toolbox` container:

`toolbox rm --force {{container_name}}`

