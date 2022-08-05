---
id: linux.toolbox-run
title: Toolbox Run
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
# toolbox run

> Run a command in an existing `toolbox` container.
> See also: `toolbox enter`.
> More information: <https://manned.org/toolbox-run>.

- Run a command inside a specific `toolbox` container:

`toolbox run --container {{container_name}} {{command}}`

- Run a command inside a `toolbox` container for a specific release of a distribution:

`toolbox run --distro {{distribution}} --release {{release}} {{command}}`

- Run `emacs` inside a `toolbox` container using the default image for Fedora 36:

`toolbox run --distro {{fedora}} --release {{f36}} {{emacs}}`

