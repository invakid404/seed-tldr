---
id: linux.sqfstar
title: Sqfstar
desc: ''
updated: 1683599668727
created: 1683599668727
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sqfstar

> Create a squashfs filesystem from a tar archive.
> More information: <https://manned.org/sqfstar>.

- Create a squashfs filesystem (compressed using `gzip` by default) from an uncompressed tar archive:

`sqfstar {{filesystem.squashfs}} < {{archive.tar}}`

- Create a squashfs filesystem from a tar archive compressed with `gzip`, and [comp]ress the filesystem using a specific algorithm:

`zcat {{archive.tar.gz}} | sqfstar -comp {{gzip|lzo|lz4|xz|zstd|lzma}} {{filesystem.squashfs}}`

- Create a squashfs filesystem from a tar archive compressed with `xz`, excluding some of the files:

`xzcat {{archive.tar.xz}} | sqfstar {{filesystem.squashfs}} {{file1 file2 ...}}`

- Create a squashfs filesystem from a tar archive compressed with `zstd`, excluding files ending with `.gz`:

`zstdcat {{archive.tar.zst}} | sqfstar {{filesystem.squashfs}} "{{*.gz}}"`

- Create a squashfs filesystem from a tar archive compressed with `lz4`, excluding files matching a regular expression:

`lz4cat {{archive.tar.lz4}} | sqfstar {{filesystem.squashfs}} -regex "{{regular_expression}}"`

