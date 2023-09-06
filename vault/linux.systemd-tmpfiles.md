---
id: linux.systemd-tmpfiles
title: Systemd Tmpfiles
desc: ''
updated: 1694027553983
created: 1694027553983
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-tmpfiles

> Create, delete and clean up volatile and temporary files and directories.
> This command is automatically invoked on boot by systemd services, and running it manually is usually not needed.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-tmpfiles.html>.

- Create files and directories as specified in the configuration:

`systemd-tmpfiles --create`

- Clean up files and directories with age parameters configured:

`systemd-tmpfiles --clean`

- Remove files and directories as specified in the configuration:

`systemd-tmpfiles --remove`

- Apply operations for user-specific configurations:

`systemd-tmpfiles --create --user`

- Execute lines marked for early boot:

`systemd-tmpfiles --create --boot`

