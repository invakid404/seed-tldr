---
id: linux.systemd-detect-virt
title: Systemd Detect Virt
desc: ''
updated: 1695011007353
created: 1695011007353
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-detect-virt

> Detect execution in a virtualized environment.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-detect-virt.html>.

- List detectable virtualization technologies:

`systemd-detect-virt --list`

- Detect virtualization, print the result and return a zero status code when running in a VM or a container, and a non-zero code otherwise:

`systemd-detect-virt`

- Silently check without printing anything:

`systemd-detect-virt --quiet`

- Only detect container virtualization:

`systemd-detect-virt --container`

- Only detect hardware virtualization:

`systemd-detect-virt --vm`

