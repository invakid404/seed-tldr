---
id: common.bzip3
title: Bzip3
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
# bzip3

> An efficient statistical file compressor.
> More information: <https://github.com/kspalaiologos/bzip3>.

- Compress a file:

`bzip3 {{path/to/file_to_compress}}`

- Decompress a file:

`bzip3 -d {{path/to/compressed_file.bz3}}`

- Decompress a file to `stdout`:

`bzip3 -dc {{path/to/compressed_file.bz3}}`

- Test the integrity of each file inside the archive file:

`bzip3 --test {{path/to/compressed_file.bz3}}`

- Show the compression ratio for each file processed with detailed information:

`bzip3 --verbose {{path/to/compressed_files.bz3}}`

- Decompress a file overwriting existing files:

`bzip3 --force {{path/to/compressed_file.bz3}}`

- Display help:

`bzip3 -h`

