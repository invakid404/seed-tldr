---
id: linux.lsusb
title: Lsusb
desc: ''
updated: 1689654011786
created: 1689654011786
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsusb

> Display information about USB buses and devices connected to them.
> More information: <https://manned.org/lsusb>.

- List all the USB devices available:

`lsusb`

- List the USB hierarchy as a tree:

`lsusb -t`

- List verbose information about USB devices:

`lsusb --verbose`

- List detailed information about a USB device:

`lsusb --verbose -s {{bus}}:{{device number}}`

- List devices with a specified vendor and product ID only:

`lsusb -d {{vendor}}:{{product}}`

