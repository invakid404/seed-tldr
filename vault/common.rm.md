---
id: common.rm
title: Rm
desc: ''
updated: 1673108584915
created: 1673108584915
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

`rm -f {{path/to/file1 path/to/file2 ...}}`

- Remove specific files [i]nteractively prompting before each removal:

`rm -i {{path/to/file1 path/to/file2 ...}}`

- Remove specific files printing info about each removal:

`rm -v {{path/to/file1 path/to/file2 ...}}`

- Remove specific files and directories [r]ecursively:

`rm -r {{path/to/file_or_directory1 path/to/file_or_directory2 ...}}`

