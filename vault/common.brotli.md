---
id: common.brotli
title: Brotli
desc: ''
updated: 1682253030909
created: 1682253030909
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# brotli

> Compress/uncompress files with Brotli compression.
> More information: <https://github.com/google/brotli>.

- Compress a file, creating a compressed version next to the file:

`brotli {{path/to/file}}`

- Decompress a file, creating an uncompressed version next to the file:

`brotli -d {{path/to/file.br}}`

- Compress a file specifying the output filename:

`brotli {{path/to/file}} -o {{path/to/compressed_output_file.br}}`

- Decompress a Brotli file specifying the output filename:

`brotli -d {{path/to/compressed_file.br}} -o {{path/to/output_file}}`

- Specify the compression level [1=Fastest (Worst), 11=Slowest (Best)]&#x3A;

`brotli -q {{11}} {{path/to/file}} -o {{path/to/compressed_output_file.br}}`

