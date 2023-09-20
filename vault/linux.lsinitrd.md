---
id: linux.lsinitrd
title: Lsinitrd
desc: ''
updated: 1695179791528
created: 1695179791528
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsinitrd

> Show the contents of an initramfs image.
> See also: `dracut`.
> More information: <https://github.com/dracutdevs/dracut/blob/master/man/lsinitrd.1.asc>.

- Show the contents of the initramfs image for the current kernel:

`lsinitrd`

- Show the contents of the initramfs image for the specified kernel:

`lsinitrd --kver {{kernel_version}}`

- Show the contents of the specified initramfs image:

`lsinitrd {{path/to/initramfs.img}}`

- List modules included in the initramfs image:

`lsinitrd --mod`

- Unpack the initramfs to the current directory:

`lsinitrd --unpack`

