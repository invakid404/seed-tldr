---
id: linux.resize2fs
title: Resize2fs
desc: ''
updated: 1656591837649
created: 1656591837649
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# resize2fs

> Resize an ext2, ext3 or ext4 filesystem.
> Does not resize the underlying partition. The filesystem may have to be unmounted first, read the man page for more details.
> More information: <https://manned.org/resize2fs>.

- Automatically resize a filesystem:

`resize2fs {{/dev/sdXN}}`

- Resize the filesystem to a size of 40G, displaying a progress bar:

`resize2fs -p {{/dev/sdXN}} {{40G}}`

- Shrink the filesystem to its minimum possible size:

`resize2fs -M {{/dev/sdXN}}`

