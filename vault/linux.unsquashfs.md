---
id: linux.unsquashfs
title: Unsquashfs
desc: ''
updated: 1684031731357
created: 1684031731357
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unsquashfs

> Uncompress, extract and list files in squashfs filesystems.
> More information: <https://manned.org/unsquashfs>.

- Extract a squashfs filesystem to `squashfs-root` in the current working directory:

`unsquashfs {{filesystem.squashfs}}`

- Extract a squashfs filesystem to the specified directory:

`unsquashfs -dest {{path/to/directory}} {{filesystem.squashfs}}`

- Display the names of files as they are extracted:

`unsquashfs -info {{filesystem.squashfs}}`

- Display the names of files and their attributes as they are extracted:

`unsquashfs -linfo {{filesystem.squashfs}}`

- List files inside the squashfs filesystem (without extracting):

`unsquashfs -ls {{filesystem.squashfs}}`

- List files and their attributes inside the squashfs filesystem (without extracting):

`unsquashfs -lls {{filesystem.squashfs}}`

