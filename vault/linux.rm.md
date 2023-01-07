---
id: linux.rm
title: Rm
desc: ''
updated: 1673108585002
created: 1673108585002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rm

> Remove files or directories.
> See also: `rmdir`.
> More information: <https://www.gnu.org/software/coreutils/rm>.

- Remove specific files:

`rm {{path/to/file1 path/to/file2 ...}}`

- Remove specific files ignoring nonexistent ones:

`rm --force {{path/to/file1 path/to/file2 ...}}`

- Remove specific files interactively prompting before each removal:

`rm --interactive {{path/to/file1 path/to/file2 ...}}`

- Remove specific files printing info about each removal:

`rm --verbose {{path/to/file1 path/to/file2 ...}}`

- Remove specific files and directories recursively:

`rm --recursive {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

