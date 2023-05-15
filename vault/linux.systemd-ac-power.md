---
id: linux.systemd-ac-power
title: Systemd Ac Power
desc: ''
updated: 1684131676782
created: 1684131676782
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-ac-power

> Report whether the computer is connected to an external power source.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-ac-power.html>.

- Silently check and return a 0 status code when running on AC power, and a non-zero code otherwise:

`systemd-ac-power`

- Additionally print `yes` or `no` to `stdout`:

`systemd-ac-power --verbose`

