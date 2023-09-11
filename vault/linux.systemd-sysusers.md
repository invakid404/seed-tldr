---
id: linux.systemd-sysusers
title: Systemd Sysusers
desc: ''
updated: 1694438414769
created: 1694438414769
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# systemd-sysusers

> Create system users and groups.
> If the config file is not specified, files in the `sysusers.d` directories are used.
> More information: <https://www.freedesktop.org/software/systemd/man/systemd-sysusers.html>.

- Create users and groups from a specific configuration file:

`systemd-sysusers {{path/to/file}}`

- Process configuration files and print what would be done without actually doing anything:

`systemd-sysusers --dry-run {{path/to/file}}`

- Print the contents of all config files (before each file, its name is printed as a comment):

`systemd-sysusers --cat-config`

