---
id: linux.xxhsum
title: Xxhsum
desc: ''
updated: 1665573834637
created: 1665573834637
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xxhsum

> Print or verify checksums using fast non-cryptographic algorithm xxHash.
> More information: <https://github.com/Cyan4973/xxHash>.

- Calculate the checksum for a file using a specific algorithm:

`xxhsum -H{{0|32|64|128}} {{path/to/file}}`

- Run benchmark:

`xxhsum -b`

