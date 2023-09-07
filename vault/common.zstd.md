---
id: common.zstd
title: Zstd
desc: ''
updated: 1694063682950
created: 1694063682950
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zstd

> Compress or decompress files with Zstandard compression.
> More information: <https://github.com/facebook/zstd>.

- Compress a file into a new file with the `.zst` suffix:

`zstd {{path/to/file}}`

- Decompress a file:

`zstd --decompress {{path/to/file.zst}}`

- Decompress to `stdout`:

`zstd --decompress --stdout {{path/to/file.zst}}`

- Compress a file specifying the compression level, where 1=fastest, 19=slowest and 3=default:

`zstd -{{level}} {{path/to/file}}`

- Unlock higher compression levels (up to 22) using more memory (both for compression and decompression):

`zstd --ultra -{{level}} {{path/to/file}}`

