---
id: linux.reboot
title: Reboot
desc: ''
updated: 1665368716265
created: 1665368716265
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# reboot

> Reboot the system.
> More information: <https://manned.org/reboot.8>.

- Reboot the system:

`reboot`

- Power off the system (same as `poweroff`):

`reboot --poweroff`

- Halt the system (same as `halt`):

`reboot --halt`

- Reboot immediately without contacting the system manager:

`reboot --force`

- Write the wtmp shutdown entry without rebooting the system:

`reboot --wtmp-only`

