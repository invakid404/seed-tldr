---
id: linux.btrfs-rescue
title: Btrfs Rescue
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
# btrfs rescue

> Try to recover a damaged btrfs filesystem.
> More information: <https://btrfs.readthedocs.io/en/latest/btrfs-rescue.html>.

- Rebuild the filesystem metadata tree (very slow):

`sudo btrfs rescue chunk-recover {{path/to/partition}}`

- Fix device size alignment related problems (e.g. unable to mount the filesystem with super total bytes mismatch):

`sudo btrfs rescue fix-device-size {{path/to/partition}}`

- Recover a corrupted superblock from correct copies (recover the root of filesystem tree):

`sudo btrfs rescue super-recover {{path/to/partition}}`

- Recover from an interrupted transactions (fixes log replay problems):

`sudo btrfs rescue zero-log {{path/to/partition}}`

- Create a `/dev/btrfs-control` control device when `mknod` is not installed:

`sudo btrfs rescue create-control-device`

