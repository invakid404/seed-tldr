---
id: linux.toolbox-enter
title: Toolbox Enter
desc: ''
updated: 1686244500730
created: 1686244500730
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# toolbox enter

> Enter a `toolbox` container for interactive use.
> See also: `toolbox run`.
> More information: <https://manned.org/toolbox-enter.1>.

- Enter a `toolbox` container using the default image of a specific distribution:

`toolbox enter --distro {{distribution}}`

- Enter a `toolbox` container using the default image of a specific release of the current distribution:

`toolbox enter --release {{release}}`

- Enter a toolbox container using the default image for Fedora 38:

`toolbox enter --distro {{fedora}} --release {{f38}}`

