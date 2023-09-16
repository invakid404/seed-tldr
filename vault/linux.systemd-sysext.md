---
id: linux.systemd-sysext
title: Systemd Sysext
desc: ''
updated: 1694898750921
created: 1694898750921
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-sysext

> Activate or deactivate system extension images.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-sysext.html>.

- List installed extension images:

`systemd-sysext list`

- Merge system extension images into `/usr/` and `/opt/`:

`systemd-sysext merge`

- Check the current merge status:

`systemd-sysext status`

- Unmerge all currently installed system extension images from `/usr/` and `/opt/`:

`systemd-sysext unmerge`

- Refresh system extension images (a combination of unmerge and merge):

`systemd-sysext refresh`

