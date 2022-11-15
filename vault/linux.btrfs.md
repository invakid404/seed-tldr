---
id: linux.btrfs
title: Btrfs
desc: ''
updated: 1668516075002
created: 1668516075002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# btrfs

> A filesystem based on the copy-on-write (COW) principle for Linux.
> Some subcommands such as `btrfs device` have their own usage documentation.
> More information: <https://btrfs.readthedocs.io/en/latest/btrfs.html>.

- Create subvolume:

`sudo btrfs subvolume create {{path/to/subvolume}}`

- List subvolumes:

`sudo btrfs subvolume list {{path/to/mount_point}}`

- Show space usage information:

`sudo btrfs filesystem df {{path/to/mount_point}}`

- Enable quota:

`sudo btrfs quota enable {{path/to/subvolume}}`

- Show quota:

`sudo btrfs qgroup show {{path/to/subvolume}}`

