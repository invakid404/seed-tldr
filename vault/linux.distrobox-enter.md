---
id: linux.distrobox-enter
title: Distrobox Enter
desc: ''
updated: 1679229162639
created: 1679229162639
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-enter

> Enter a distrobox container. See also: `tldr distrobox`.
> Default command executed is your SHELL, but you can specify different shells or entire commands to execute. If used inside a script, an application, or a service, you can use the `--headless` mode to disable the tty and interactivity.
> More information: <https://distrobox.privatedns.org/usage/distrobox-enter.html>.

- Enter a distrobox container:

`distrobox-enter {{container_name}}`

- Enter a distrobox container and run a command at login:

`distrobox-enter {{container_name}} -- {{sh -l}}`

- Enter a distrobox container without instantiating a tty:

`distrobox-enter --name {{container_name}} -- {{uptime -p}}`

