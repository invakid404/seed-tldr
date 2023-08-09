---
id: linux.rmmod
title: Rmmod
desc: ''
updated: 1691562059184
created: 1691562059184
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rmmod

> Remove modules from the Linux kernel.
> More information: <https://manned.org/rmmod>.

- Remove a module from the kernel:

`sudo rmmod {{module_name}}`

- Remove a module from the kernel and display verbose information:

`sudo rmmod --verbose {{module_name}}`

- Remove a module from the kernel and send errors to syslog instead of `stderr`:

`sudo rmmod --syslog {{module_name}}`

- Display help:

`rmmod --help`

- Display version:

`rmmod --version`

