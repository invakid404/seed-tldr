---
id: osx.diskutil
title: Diskutil
desc: ''
updated: 1676877466489
created: 1676877466489
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# diskutil

> Utility to manage local disks and volumes.
> More information: <https://ss64.com/osx/diskutil.html>.

- List all currently available disks, partitions and mounted volumes:

`diskutil list`

- Repair the filesystem data structures of a volume:

`diskutil repairVolume {{/dev/disk_device}}`

- Unmount a volume:

`diskutil unmountDisk {{/dev/disk_device}}`

- Eject a CD/DVD (unmount first):

`diskutil eject {{/dev/disk_device1}}`

