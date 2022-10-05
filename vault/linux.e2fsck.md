---
id: linux.e2fsck
title: E2fsck
desc: ''
updated: 1664955321150
created: 1664955321150
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# e2fsck

> Check a Linux ext2/ext3/ext4 filesystem. The partition should be unmounted.
> More information: <https://manned.org/e2fsck>.

- Check filesystem, reporting any damaged blocks:

`sudo e2fsck {{/dev/sdXN}}`

- Check filesystem and automatically repair any damaged blocks:

`sudo e2fsck -p {{/dev/sdXN}}`

- Check filesystem in read only mode:

`sudo e2fsck -c {{/dev/sdXN}}`

- Perform an exhaustive, non-destructive read-write test for bad blocks and blacklist them:

`sudo e2fsck -fccky {{/dev/sdXN}}`

