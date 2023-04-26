---
id: linux.oomctl
title: Oomctl
desc: ''
updated: 1682500599018
created: 1682500599018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# oomctl

> Analyze the state stored in `systemd-oomd`.
> More information: <https://www.freedesktop.org/software/systemd/man/oomctl.html>.

- Show the current state of the cgroups and system contexts stored by `systemd-oomd`:

`oomctl dump`

