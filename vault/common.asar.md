---
id: common.asar
title: Asar
desc: ''
updated: 1681453285394
created: 1681453285394
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asar

> A file archiver for the Electron platform.
> More information: <https://github.com/electron/asar>.

- Archive a file or directory:

`asar pack {{path/to/input_file_or_directory}} {{path/to/output_archive.asar}}`

- Extract an archive:

`asar extract {{path/to/archive.asar}}`

- Extract a specific file from an archive:

`asar extract-file {{path/to/archive.asar}} {{file}}`

- List the contents of an archive file:

`asar list {{path/to/archive.asar}}`

