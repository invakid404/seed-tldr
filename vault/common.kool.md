---
id: common.kool
title: Kool
desc: ''
updated: 1664762512945
created: 1664762512945
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kool

> Build software development environments from the command-line.
> More information: <https://kool.dev/docs/>.

- Create a project using a specific preset:

`kool create {{preset}} {{project_name}}`

- Run a specific script defined in the `kool.yml` file in the current directory:

`kool run {{script}}`

- Start/stop services in the current directory:

`kool {{start|stop}}`

- Display status of the services in the current directory:

`kool status`

- Update to the latest version:

`kool self-update`

- Print the completion script for the specified shell:

`kool completion {{bash|fish|powershell|zsh}}`

