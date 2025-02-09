---
id: common.zip
title: Zip
desc: ''
updated: 1666107123546
created: 1666107123546
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zip

> Package and compress (archive) files into zip file.
> See also: `unzip`.
> More information: <https://manned.org/zip>.

- Add files/directories to a specific archive ([r]ecursively):

`zip -r {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Remove files/directories from a specific archive ([d]elete):

`zip -d {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Archive files/directories e[x]cluding specified ones:

`zip -r {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}} -x {{path/to/excluded_files_or_directories}}`

- Archive files/directories with a specific compression level (`0` - the lowest, `9` - the highest):

`zip -r -{{0-9}} {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Create an [e]ncrypted archive with a specific password:

`zip -r -e {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Archive files/directories to a multi-part [s]plit zip file (e.g. 3 GB parts):

`zip -r -s {{3g}} {{path/to/compressed.zip}} {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

- Print a specific archive contents:

`zip -sf {{path/to/compressed.zip}}`

