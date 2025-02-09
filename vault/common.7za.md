---
id: common.7za
title: 7za
desc: ''
updated: 1684413160651
created: 1684413160651
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# 7za

> File archiver with a high compression ratio.
> Similar to `7z` except that it supports fewer file types but is cross-platform.
> More information: <https://manned.org/7za>.

- [a]rchive a file or directory:

`7za a {{path/to/archive.7z}} {{path/to/file_or_directory}}`

- Encrypt an existing archive (including file names):

`7za a {{path/to/encrypted.7z}} -p{{password}} -mhe={{on}} {{path/to/archive.7z}}`

- E[x]tract an archive preserving the original directory structure:

`7za x {{path/to/archive.7z}}`

- E[x]tract an archive to a specific directory:

`7za x {{path/to/archive.7z}} -o{{path/to/output}}`

- E[x]tract an archive to `stdout`:

`7za x {{path/to/archive.7z}} -so`

- [a]rchive using a specific archive type:

`7za a -t{{7z|bzip2|gzip|lzip|tar|...}} {{path/to/archive.7z}} {{path/to/file_or_directory}}`

- [l]ist the contents of an archive:

`7za l {{path/to/archive.7z}}`

- List available archive types:

`7za i`

