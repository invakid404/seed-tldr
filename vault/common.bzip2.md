---
id: common.bzip2
title: Bzip2
desc: ''
updated: 1691562058929
created: 1691562058929
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bzip2

> A block-sorting file compressor.
> More information: <https://manned.org/bzip2>.

- Compress a file:

`bzip2 {{path/to/file_to_compress}}`

- Decompress a file:

`bzip2 -d {{path/to/compressed_file.bz2}}`

- Decompress a file to `stdout`:

`bzip2 -dc {{path/to/compressed_file.bz2}}`

- Test the integrity of each file inside the archive file:

`bzip2 --test {{path/to/compressed_file.bz2}}`

- Show the compression ratio for each file processed with detailed information:

`bzip2 --verbose {{path/to/compressed_files.bz2}}`

- Decompress a file overwriting existing files:

`bzip2 --force {{path/to/compressed_file.bz2}}`

- Display help:

`bzip2 -h`

