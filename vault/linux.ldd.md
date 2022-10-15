---
id: linux.ldd
title: Ldd
desc: ''
updated: 1665841424987
created: 1665841424987
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ldd

> Display shared library dependencies of a binary.
> Do not use on an untrusted binary, use objdump for that instead.
> More information: <https://manned.org/ldd>.

- Display shared library dependencies of a binary:

`ldd {{path/to/binary}}`

- Display all information about dependencies:

`ldd --verbose {{path/to/binary}}`

- Display unused direct dependencies:

`ldd --unused {{path/to/binary}}`

- Report missing data objects and perform data relocations:

`ldd --data-relocs {{path/to/binary}}`

- Report missing data objects and functions, and perform relocations for both:

`ldd --function-relocs {{path/to/binary}}`

