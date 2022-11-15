---
id: linux.btrfs-inspect-internal
title: Btrfs Inspect Internal
desc: ''
updated: 1668516075001
created: 1668516075001
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# btrfs inspect-internal

> Query internal information of a btrfs filesystem.
> More information: <https://btrfs.readthedocs.io/en/latest/btrfs-inspect-internal.html>.

- Print superblock's information:

`sudo btrfs inspect-internal dump-super {{path/to/partition}}`

- Print superblock's and all of its copies' information:

`sudo btrfs inspect-internal dump-super --all {{path/to/partition}}`

- Print filesystem's metadata information:

`sudo btrfs inspect-internal dump-tree {{path/to/partition}}`

- Print list of files in inode `n`-th:

`sudo btrfs inspect-internal inode-resolve {{n}} {{path/to/btrfs_mount}}`

- Print list of files at a given logical address:

`sudo btrfs inspect-internal logical-resolve {{logical_address}} {{path/to/btrfs_mount}}`

- Print stats of root, extent, csum and fs trees:

`sudo btrfs inspect-internal tree-stats {{path/to/partition}}`

